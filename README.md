# はじめて触る Docker・Kubernetes
![GitHub Workflow Status (with event)](https://img.shields.io/github/actions/workflow/status/mu-ruU1/docker-kubernetes-tutorial/custom_image_build.yaml?style=for-the-badge)
![GitHub release (with filter)](https://img.shields.io/github/v/release/mu-ruU1/docker-kubernetes-tutorial?style=for-the-badge)
![GitHub Release Date - Published_At](https://img.shields.io/github/release-date/mu-ruU1/docker-kubernetes-tutorial?style=for-the-badge)
  
[![dockeri.co](https://dockerico.blankenship.io/image/muruu1/echo-pods)](https://hub.docker.com/r/muruu1/echo-pods)

## Docker 環境構築

1. [Docker, Docker Compose のインストール](./docs/install-docker.md)

## Kubernetes 環境構築

1. [Proxmox VE に k8s で用いる VM の作成](./docs/terraform.md)
2. [kubeadm を用いた k8s クラスタの構築](./docs/setup-k8s-common.md)

## ディレクトリ構成

- [`docs`](./docs/)
  - docker と kubernetes の構築方法など
  - スライドで使用した図を draw.io で描いて管理する
- [`sample`](./sample/)
  - [`01_echo-pods`](./sample/01_echo-pods/)
    - Pod の情報を出力する
    - Docker と Kubernetes のマニフェストファイルを管理している
  - [`02_cmd-entrypoint`](./sample/02_cmd-entrypoint/)
    - CMD と ENTRYPOINT の動作の比較
    - 比較用の Dockerfile を管理している
  - [`03_buildkit`](./sample/03_buildkit/)
    - Buildkit を利用したもの
    - サンプルの Dockerfile を管理している
  - [`04_argocd`](./sample/04_argocd)
    - Argo CD で使用するマニフェストファイルを管理している
- [`terraform`](./terraform/)
  - Kubernetes で利用する仮想マシンを Proxmox VE に作成する
