# docker_cakephp3_tutorial

Docker-Composeを利用してCakePHP3のチュートリアルを行うための環境を構築します。  
自分のメモ用ですので、動作を保証しません。

# Required

* Docker
* Docker Compose
* Docker Machine

# Environment

* Mac OS X 10.11
* Docker 1.11.1
* Docker Compose 1.7.0
* Docker Machine 0.7.0

# How To Run

```bash
docker-machine up
eval $(docker-machine env)
docker-compose up -d
```

# License

MIT License.
See [LICENSE](LICENSE).

