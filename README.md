## Para gerar um token randomico
```bash
node -e "console.log(require('crypto').randomBytes(64).toString('Hex'))"
```