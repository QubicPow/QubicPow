
| OS    | runtime environment installation |
| ------ | ------ |
| Windows |[dotnet-runtime-6.0](https://download.visualstudio.microsoft.com/download/pr/fb0630a0-d5e7-43a6-92eb-1e114de80a5b/a43563f0a5c6ca71005d8ffe5de1bd88/dotnet-runtime-6.0.28-win-x64.exe)|
| Linux | sudo apt-get install -y dotnet-runtime-6.0|

-------------------------------------------
| OS    | DownLoad  |
| ------ | ------ |
| Windows |[Qubic_windows](https://github.com/QubicPow/QubicPow/raw/main/windows.zip) |
| Linux | [Qubic_Linux](https://github.com/QubicPow/QubicPow/raw/main/Linux.tar)|
-------------------------------------------

|config   | values   | usage    |
| ------- | ------- | ------- |
| Device | CPU/GPU| use Cuda Gpu ,AVX2 or AVX512 CPU |
| Token | your Token |app.qubic.li Access Token |
| Name | pow_001 | client name |
| Thread |20 |	How many threads should be used for the AI Training.|

-------------------------------------------
If you want to use GPU in Windows, you can install WSL.
Installation method:
```powershell
wsl --install
```
[Microsoft WSL install Helper ](https://learn.microsoft.com/zh-cn/windows/wsl/install)

-------------------------------------------
**WSL Ubuntu22.04:**
```bash
sudo apt-get update && \
  sudo apt-get install -y dotnet-runtime-6.0
```
```bash
mkdir ~/qubicclient
```
```bash
cd ~/qubicclient
```
```bash
wget https://github.com/QubicPow/QubicPow/raw/main/Linux.tar
```
```bash
tar -xvf Linux.tar
```
Edit conf.conf
```bash
vi conf.conf
```
```bash
./qubicClient
```




