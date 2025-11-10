# Ubuntu 22.04
- OS Version: 22.04.5 LTS
- Kernel Version: 6.8.0-1041-azure
- Image Version: 0.0.1
- Systemd version: 249.11-0ubuntu3.17

## Installed Software

### Language and Runtime
- Bash 5.1.16(1)-release
- Clang: 14.0.0, 15.0.7
- Clang-format: 14.0.0, 15.0.7
- Clang-tidy: 14.0.0, 15.0.7
- Dash 0.5.11+git20210903+057cd650a4ed-3build1
- GNU C++: 10.5.0, 11.4.0, 12.3.0, 13.1.0
- GNU Fortran: 10.5.0, 11.4.0, 12.3.0
- Kotlin 2.2.21-release-469
- Mono 6.12.0.200
- MSBuild 16.10.1.31701 (Mono 6.12.0.200)
- Node.js 20.19.5
- Perl 5.34.0
- Python 3.10.12
- Ruby 3.0.2p107
- Swift 6.2

### Package Management
- Helm 3.19.0
- Npm 10.8.2
- NuGet 6.6.1.2
- Pip 22.0.2
- Pip3 22.0.2
- Pipx 1.8.0
- RubyGems 3.3.5
- Vcpkg (build from commit 68b1b31e03)
- Yarn 1.22.22

#### Environment variables
| Name                    | Value                  |
| ----------------------- | ---------------------- |
| CONDA                   |                        |
| VCPKG_INSTALLATION_ROOT | /usr/local/share/vcpkg |

### Project Management
- Ant 1.10.12
- Gradle 4.4.1
- Lerna 9.0.0
- Maven 3.9.11

### Tools
- Ansible 2.17.14
- apt-fast 1.10.0
- AzCopy 10.30.1 - available by `azcopy` and `azcopy10` aliases
- Bazel 8.4.2
- Bazelisk 1.26.0
- Buildah 1.23.1
- CMake 3.31.6
- Docker Amazon ECR Credential Helper 0.10.1
- Docker Compose v2 2.38.2
- Docker-Buildx 0.29.1
- Docker Client 28.0.4
- Docker Server 28.0.4
- Git 2.51.1
- Git LFS 3.7.1
- Git-ftp 1.6.0
- Haveged 1.9.14
- jq 1.6
- Kind 0.30.0
- Kubectl 1.34.1
- Kustomize 5.7.1
- OpenSSL 3.0.2-0ubuntu1.20
- Packer 1.14.2
- Podman 3.4.4
- Pulumi 3.204.0
- Skopeo 1.4.1
- SVN 1.14.1
- Terraform 1.13.4
- yamllint 1.37.1
- yq 4.48.1
- zstd 1.5.7
- Ninja 1.12.1

### CLI Tools
- AWS CLI 2.31.22
- AWS CLI Session Manager Plugin 1.2.707.0
- AWS SAM CLI 1.145.2
- Azure CLI 2.78.0
- Azure CLI (azure-devops) 1.0.2
- GitHub CLI 2.82.1
- Google Cloud CLI 544.0.0
- Vercel CLI 48.6.0

### Java
| Version             | Environment Variable |
| ------------------- | -------------------- |
| 8.0.462+8           | JAVA_HOME_8_X64      |
| 11.0.28+6 (default) | JAVA_HOME_11_X64     |
| 17.0.17+10          | JAVA_HOME_17_X64     |
| 21.0.8+9            | JAVA_HOME_21_X64     |
| 25.0.0+36           | JAVA_HOME_25_X64     |

### PHP Tools
- PHP: 8.1.33
- Composer 2.8.12
- PHPUnit 8.5.48
```
Both Xdebug and PCOV extensions are installed, but only Xdebug is enabled.
```

### Rust Tools
- Cargo 1.90.0
- Rust 1.90.0
- Rustdoc 1.90.0
- Rustup 1.28.2

#### Packages
- Bindgen 0.72.1
- Cargo audit 0.21.2
- Cargo clippy 0.1.90
- Cargo outdated 0.17.0
- Cbindgen 0.29.2
- Rustfmt 1.8.0

### .NET Tools
- .NET Core SDK: 8.0.121, 8.0.206, 8.0.318, 8.0.415
- nbgv 3.8.118+69b3e0b5a0

### Databases
- sqlite3 3.37.2

#### MySQL
- MySQL 8.0.43-0ubuntu0.22.04.2
```
User: root
Password: root
MySQL service is disabled by default.
Use the following command as a part of your job to start the service: 'sudo systemctl start mysql.service'
```

### PowerShell Tools
- PowerShell 7.4.6

#### PowerShell Modules
- Az: 12.5.0
- MarkdownPS: 1.10
- Microsoft.Graph: 2.32.0
- Pester: 5.7.1
- PSScriptAnalyzer: 1.24.0

### Cached Docker images
| Repository:Tag       | Digest                                                                   | Created    |
| -------------------- | ------------------------------------------------------------------------ | ---------- |
| alpine:3.16          | sha256:452e7292acee0ee16c332324d7de05fa2c99f9994ecc9f0779c602916a672ae4  | 2024-01-26 |
| alpine:3.17          | sha256:8fc3dacfb6d69da8d44e42390de777e48577085db99aa4e4af35f483eb08b989  | 2024-09-06 |
| alpine:3.18          | sha256:de0eb0b3f2a47ba1eb89389859a9bd88b28e82f5826b6969ad604979713c2d4f  | 2025-02-14 |
| alpine:3.19          | sha256:6baf43584bcb78f2e5847d1de515f23499913ac9f12bdf834811a3145eb11ca1  | 2025-10-08 |
| debian:10            | sha256:58ce6f1271ae1c8a2006ff7d3e54e9874d839f573d8009c20154ad0f2fb0a225  | 2024-06-13 |
| debian:11            | sha256:5e2b4654ea0dc0bc22434199dace15adf9799f292857679fa79f9395e6d4dafd  | 2025-10-20 |
| moby/buildkit:latest | sha256:79cc6476ab1a3371c9afd8b44e7c55610057c43e18d9b39b68e2b0c2475cc1b6  | 2025-10-07 |
| node:18              | sha256:c6ae79e38498325db67193d391e6ec1d224d96c693a8a4d943498556716d3783  | 2025-03-27 |
| node:18-alpine       | sha256:8d6421d663b4c28fd3ebc498332f249011d118945588d0a35cb9bc4b8ca09d9e  | 2025-03-27 |
| node:20              | sha256:c11ae157cdd9f8b522d5a65e7f3f5f5c34cf45a8bd883c15e8f2028a2673dec7  | 2025-10-16 |
| node:20-alpine       | sha256:6178e78b972f79c335df281f4b7674a2d85071aae2af020ffa39f0a770265435  | 2025-10-16 |
| node:22              | sha256:23c24e85395992be118734a39903e08c8f7d1abc73978c46b6bda90060091a49  | 2025-10-21 |
| node:22-alpine       | sha256:bd26af08779f746650d95a2e4d653b0fd3c8030c44284b6b98d701c9b5eb66b9  | 2025-10-21 |
| ubuntu:20.04         | sha256:8feb4d8ca5354def3d8fce243717141ce31e2c428701f6682bd2fafe15388214  | 2025-04-08 |
| ubuntu:22.04         | sha256:09506232a8004baa32c47d68f1e5c307d648fdd59f5e7eaa42aaf87914100db3  | 2025-10-01 |

### Installed apt packages
| Name                   | Version                             |
| ---------------------- | ----------------------------------- |
| acl                    | 2.3.1-1                             |
| aria2                  | 1.36.0-1                            |
| autoconf               | 2.71-2                              |
| automake               | 1:1.16.5-1.3                        |
| binutils               | 2.38-4ubuntu2.8                     |
| bison                  | 2:3.8.2+dfsg-1build1                |
| brotli                 | 1.0.9-2build6                       |
| bzip2                  | 1.0.8-5build1                       |
| coreutils              | 8.32-4.1ubuntu1.2                   |
| curl                   | 7.81.0-1ubuntu1.21                  |
| dbus                   | 1.12.20-2ubuntu4.1                  |
| dnsutils               | 1:9.18.39-0ubuntu0.22.04.2          |
| dpkg                   | 1.21.1ubuntu2.6                     |
| dpkg-dev               | 1.21.1ubuntu2.6                     |
| fakeroot               | 1.28-1ubuntu1                       |
| file                   | 1:5.41-3ubuntu0.1                   |
| findutils              | 4.8.0-1ubuntu3                      |
| flex                   | 2.6.4-8build2                       |
| fonts-noto-color-emoji | 2.047-0ubuntu0.22.04.1              |
| ftp                    | 20210827-4build1                    |
| g++                    | 4:11.2.0-1ubuntu1                   |
| gcc                    | 4:11.2.0-1ubuntu1                   |
| gnupg2                 | 2.2.27-3ubuntu2.4                   |
| golang-go              | 2:1.18\~0ubuntu2                    |
| haveged                | 1.9.14-1ubuntu1                     |
| imagemagick            | 8:6.9.11.60+dfsg-1.3ubuntu0.22.04.5 |
| iproute2               | 5.15.0-1ubuntu2                     |
| iputils-ping           | 3:20211215-1ubuntu0.1               |
| jq                     | 1.6-2.1ubuntu3.1                    |
| libc++-dev             | 1:14.0-55\~exp2                     |
| libc++abi-dev          | 1:14.0-55\~exp2                     |
| libc6-dev              | 2.35-0ubuntu3.11                    |
| libcurl4               | 7.81.0-1ubuntu1.21                  |
| libgbm-dev             | 23.2.1-1ubuntu3.1\~22.04.3          |
| libgconf-2-4           | 3.2.6-7ubuntu2                      |
| libgsl-dev             | 2.7.1+dfsg-3                        |
| libgtk-3-0             | 3.24.33-1ubuntu2.2                  |
| libmagic-dev           | 1:5.41-3ubuntu0.1                   |
| libmagickcore-dev      | 8:6.9.11.60+dfsg-1.3ubuntu0.22.04.5 |
| libmagickwand-dev      | 8:6.9.11.60+dfsg-1.3ubuntu0.22.04.5 |
| libnss3-tools          | 2:3.98-0ubuntu0.22.04.2             |
| libsecret-1-dev        | 0.20.5-2                            |
| libsqlite3-dev         | 3.37.2-2ubuntu0.5                   |
| libssl-dev             | 3.0.2-0ubuntu1.20                   |
| libtool                | 2.4.6-15build2                      |
| libunwind8             | 1.3.2-2build2.1                     |
| libxkbfile-dev         | 1:1.1.0-1build3                     |
| libxss1                | 1:1.2.3-1build2                     |
| libyaml-dev            | 0.2.2-1build2                       |
| locales                | 2.35-0ubuntu3.11                    |
| lz4                    | 1.9.3-2build2                       |
| m4                     | 1.4.18-5ubuntu2                     |
| make                   | 4.3-4.1build1                       |
| mediainfo              | 22.03-1                             |
| mercurial              | 6.1.1-1ubuntu1                      |
| net-tools              | 1.60+git20181103.0eebece-1ubuntu5.4 |
| netcat                 | 1.218-4ubuntu1                      |
| openssh-client         | 1:8.9p1-3ubuntu0.13                 |
| p7zip-full             | 16.02+dfsg-8                        |
| p7zip-rar              | 16.02-3build1                       |
| parallel               | 20210822+ds-2                       |
| pass                   | 1.7.4-5                             |
| patchelf               | 0.14.3-1                            |
| pigz                   | 2.6-1                               |
| pkg-config             | 0.29.2-1ubuntu3                     |
| pollinate              | 4.33-3ubuntu2.1                     |
| python-is-python3      | 3.9.2-2                             |
| rpm                    | 4.17.0+dfsg1-4build1                |
| rsync                  | 3.2.7-0ubuntu0.22.04.4              |
| shellcheck             | 0.8.0-2                             |
| sphinxsearch           | 2.2.11-8                            |
| sqlite3                | 3.37.2-2ubuntu0.5                   |
| ssh                    | 1:8.9p1-3ubuntu0.13                 |
| sshpass                | 1.09-1                              |
| subversion             | 1.14.1-3ubuntu0.22.04.1             |
| sudo                   | 1.9.9-1ubuntu2.5                    |
| swig                   | 4.0.2-1ubuntu1                      |
| systemd-coredump       | 249.11-0ubuntu3.17                  |
| tar                    | 1.34+dfsg-1ubuntu0.1.22.04.2        |
| telnet                 | 0.17-44build1                       |
| texinfo                | 6.8-4build1                         |
| time                   | 1.9-0.1build2                       |
| tk                     | 8.6.11+1build2                      |
| tzdata                 | 2025b-0ubuntu0.22.04.1              |
| unzip                  | 6.0-26ubuntu3.2                     |
| upx                    | 3.96-3                              |
| wget                   | 1.21.2-2ubuntu1.1                   |
| xorriso                | 1.5.4-2                             |
| xvfb                   | 2:21.1.4-2ubuntu1.7\~22.04.15       |
| xz-utils               | 5.2.5-2ubuntu1                      |
| zip                    | 3.0-12build2                        |
| zsync                  | 0.6.2-3ubuntu1                      |
