# Carteirinha Digital — Juan Lourenco

PWA mobile de carteirinha de meia passagem.

## Personalizar dados

Abra `index.html` e edite o objeto `STUDENT` no início do `<script>`:

```js
const STUDENT = {
  name:        'Juan Lourenco',
  course:      'Administração',         // seu curso
  ra:          '2024001234',            // seu RA / matrícula
  institution: 'Universidade Anhembi',  // nome da instituição
  validity:    '12/2025',               // validade MM/AAAA
  qrData:      'MEIA:2024001234:...',   // dados codificados no QR
};
```

## Subir no GitHub Pages

1. Crie um repositório no GitHub (público)
2. Suba todos os arquivos desta pasta:
   ```bash
   cd carteirinha-juan
   git init
   git add .
   git commit -m "feat: carteirinha digital"
   git remote add origin https://github.com/SEU_USUARIO/SEU_REPO.git
   git push -u origin main
   ```
3. No repositório → **Settings → Pages → Source: GitHub Actions**
4. O app ficará disponível em:
   `https://SEU_USUARIO.github.io/SEU_REPO/`

## Instalar como app no iPhone

1. Abra a URL no Safari
2. Toque em **Compartilhar** → **Adicionar à Tela de Início**
3. O app instala como PWA (ícone na home, tela cheia, funciona offline)
