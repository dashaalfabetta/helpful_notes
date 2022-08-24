# helpful_notes

## ssh

### 1. где находятся файлы с ssh-ключами на компьютере

```bash
cd ~/.ssh/
```

### 2. содержимое папки

```bash
ls -l ~/.ssh/
```

**id_rsa.pub** - публичный ключ

**id_rsa** - приватный ключ

### 3. посмотреть ssh-ключ

```bash
cat id_rsa.pub
cat id_rsa
```

### 4. посмотреть ssh-ключи в gitlab/github

`profile -> settings -> SSH & GPG keys`
