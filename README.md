# nuxt3-docker-hot-reload
Nuxt3&Dockerのホットリロード検証

# 元記事
https://zenn.dev/harusame0616/articles/6c15d80ea39f76

# How to resolve
https://github.com/nuxt/nuxt/issues/12748#issuecomment-1397234516

docker-compose.ymlで、portの設定を `3000:3000` にしているとHMRが正しく検知されない。
`24678:3000` にすることで、HMRが走ることを確認。
