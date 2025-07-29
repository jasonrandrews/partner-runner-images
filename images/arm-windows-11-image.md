# Windows 11 by Arm Limited 

The Windows 11 Arm image is created from the [GitHub Actions Runner Images](https://github.com/actions/runner-images) repository.

Some changes have been made to accommodate for the Arm architecture. 
- Some tools do not support Arm and are not available

If you would like something added or would like to propose a substitute for something that does not work on Arm, please open an issue in this repo.

# Windows 11 Enterprise
- OS Version: 10.0.26100 Build 4656
- SKU: win11-24h2-ent 

## Installed Software

### Language and Runtime
- Bash 5.2.37(1)-release
- Go 1.24.5
- Julia 1.11.6
- Kotlin 2.2.0
- LLVM 20.1.6
- Node 22.17.1
- Perl 5.32.1
- PHP 8.4.8
- Python 3.12.10
- Ruby 3.3.8

### Package Management
- Chocolatey 2.5.0
- Composer 2.8.10
- Helm 3.18.4
- NPM 10.9.2
- NuGet 6.14.0.116
- pip 25.1.1 (python 3.12)
- Pipx 1.7.1
- RubyGems 3.5.22
- Vcpkg (build from commit c0f2272fa7)
- Yarn 1.22.22

#### Environment variables
| Name                    | Value    |
| ----------------------- | -------- |
| VCPKG_INSTALLATION_ROOT | C:\vcpkg |

### Project Management
- Ant 1.10.15
- Gradle 8.14
- Maven 3.9.11
- sbt 1.11.3

### Tools
- 7zip 25.00
- aria2 1.37.0
- azcopy 10.29.1
- Bazel 8.3.1
- Bazelisk 1.26.0
- Bicep 0.36.177
- CMake 3.31.8
- CodeQL Action Bundle 2.22.1
- Git 2.50.1.windows.1
- Git LFS 3.7.0
- ImageMagick 7.1.2-0
- InnoSetup 6.4.0
- jq 1.8.1
- Kind 0.29.0
- Kubectl 1.33.3
- Mercurial 5.0
- gcc 12.2.0
- gdb 11.2
- GNU Binutils 2.39
- Newman 6.2.1
- NSIS 3.10
- OpenSSL 3.4.2
- Packer 1.12.0
- Pulumi 3.185.0
- R 4.4.2
- Stack 3.7.1
- Swig 4.1.1
- VSWhere 3.1.7
- WinAppDriver 1.2.2009.02003
- yamllint 1.37.1
- Ninja 1.12.1

### CLI Tools
- Alibaba Cloud CLI 3.0.291
- AWS CLI 2.27.56
- AWS SAM CLI 1.142.1
- AWS Session Manager CLI 1.2.707.0
- Azure CLI 2.75.0
- Azure DevOps CLI extension 1.0.2
- GitHub CLI 2.76.1

### Rust Tools
- Cargo 1.88.0
- Rust 1.88.0
- Rustdoc 1.88.0
- Rustup 1.28.2

#### Packages
- bindgen 0.72.0
- cargo-audit 0.21.2
- cargo-outdated 0.17.0
- cbindgen 0.29.0
- Clippy 0.1.88
- Rustfmt 1.8.0

### Browsers and Drivers
- Google Chrome 138.0.7204.169
- Chrome Driver 138.0.7204.168
- Microsoft Edge 138.0.3351.95
- Microsoft Edge Driver 138.0.3351.95
- Mozilla Firefox 141.0
- Gecko Driver 0.36.0
- IE Driver 4.14.0.0
- Selenium server 4.34.0

#### Environment variables
| Name              | Value                              |
| ----------------- | ---------------------------------- |
| CHROMEWEBDRIVER   | C:\SeleniumWebDrivers\ChromeDriver |
| EDGEWEBDRIVER     | C:\SeleniumWebDrivers\EdgeDriver   |
| GECKOWEBDRIVER    | C:\SeleniumWebDrivers\GeckoDriver  |
| SELENIUM_JAR_PATH | C:\selenium\selenium-server.jar    |

### Java
| Version              | Environment Variable |
| -------------------- | -------------------- |
| 21.0.8+9.0 (default) | JAVA_HOME_21_AARCH64 |
| 23.0.2+7             | JAVA_HOME_23_AARCH64 |

### Cached Tools

#### Go
- 1.22.12
- 1.23.11
- 1.24.5

#### Node.js
- 20.19.4
- 22.17.1

#### Python
- 3.12.10
- 3.13.5

#### Ruby
- 3.3.8
- 3.4.4

### Database tools
- Azure CosmosDb Emulator 2.14.24.0
- DacFx 170.0.94.3
- MySQL 8.0.43.0
- SQL OLEDB Driver 18.7.4.0

### Web Servers
| Name   | Version | ConfigFile                            | ServiceName | ServiceStatus | ListenPort |
| ------ | ------- | ------------------------------------- | ----------- | ------------- | ---------- |
| Apache | 2.4.55  | C:\tools\Apache24\conf\httpd.conf     | Apache      | Stopped       | 80         |
| Nginx  | 1.29.0  | C:\tools\nginx-1.29.0\conf\nginx.conf | nginx       | Stopped       | 80         |

### Visual Studio Enterprise 2022
| Name                          | Version        | Path                                                     |
| ----------------------------- | -------------- | -------------------------------------------------------- |
| Visual Studio Enterprise 2022 | 17.14.36310.24 | C:\Program Files\Microsoft Visual Studio\2022\Enterprise |

#### Installed Windows SDKs
- 10.0.19041.0
- 10.0.20348.0
- 10.0.22000.0
- 10.0.26100.0

### .NET Core Tools
- .NET Core SDK: 6.0.136, 6.0.203, 6.0.321, 6.0.428, 8.0.118, 8.0.206, 8.0.315, 8.0.412, 9.0.108, 9.0.205, 9.0.302, 9.0.303
- .NET Framework: 4.7.2, 4.8, 4.8.1
- Microsoft.AspNetCore.App: 6.0.5, 6.0.26, 6.0.36, 8.0.6, 8.0.18, 9.0.6, 9.0.7
- Microsoft.NETCore.App: 6.0.5, 6.0.26, 6.0.36, 8.0.6, 8.0.18, 9.0.6, 9.0.7
- Microsoft.WindowsDesktop.App: 6.0.5, 6.0.26, 6.0.36, 8.0.6, 8.0.18, 9.0.6, 9.0.7
- nbgv 3.7.115+d31f50f4d1

### PowerShell Tools
- PowerShell 7.4.11

#### Powershell Modules
- Az: 12.5.0
- AWSPowershell: 5.0.17
- DockerMsftProvider: 1.0.0.8
- MarkdownPS: 1.10
- Microsoft.Graph: 2.29.1
- Pester: 3.4.0, 5.7.1
- PowerShellGet: 1.0.0.1, 2.2.5
- PSScriptAnalyzer: 1.24.0
- PSWindowsUpdate: 2.2.1.5
- SqlServer: 22.4.5.1
- VSSetup: 2.2.16


## Omitted software

This section lists tools which are installed on [Windows 2022 X86 image](https://github.com/actions/runner-images/blob/main/images/windows/Windows2022-Readme.md) provided by GitHub but omitted from the current image.

-  Tools that are not available on Windows 11 Arm image
    - Android
    - Cabal
    - Docker
    - Docker Compose
    - Docker-wincred
    - Cached Docker images
    - ghc
    - Microsoft SQL client tools
    - Miniconda
    - Service Fabric SDK
    - Subversion (SVN)
    - WiX Toolset
    - zstd
    - PostgreSQL
    - MongoDB
    - Haskell
    - PyPy
    - Msys2
    - pacman
    - SQLPS
