# website

KSA の公式サイトです。

## Contribution

静的 HTML なので、そのまま編集してください。

## Deploy

Firebase Hosting を使っています。

https://console.firebase.google.com/u/0/project/student-kyushu2020/overview

GitHub Actions により、master にプッシュされた場合に Firebase Hosting にデプロイされます。

### Local

手元でデプロイする場合

```bash
curl -sL https://firebase.tools | bash
firebase login
firebase deploy
```

GitHub Actions の FIREBASE_TOKEN を更新する場合

```bash
firebase login:ci
```
