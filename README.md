# TreinoTrack PWA

App de treino 100% offline, instalável na tela inicial do Android.

## Arquivos

```
treino-pwa/
├── index.html      ← App completo
├── manifest.json   ← Configuração do PWA
├── sw.js           ← Service Worker (offline)
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Como hospedar GRÁTIS no GitHub Pages

### Passo a passo

1. Crie uma conta em https://github.com (se não tiver)

2. Clique em **"New repository"**
   - Nome: `treino-pwa` (ou qualquer nome)
   - Deixe **Public**
   - Clique em **Create repository**

3. Clique em **"uploading an existing file"** na página do repositório

4. Arraste todos os arquivos da pasta `treino-pwa/` incluindo a pasta `icons/`
   - index.html
   - manifest.json
   - sw.js
   - icons/icon-192.png
   - icons/icon-512.png

5. Clique em **Commit changes**

6. Vá em **Settings → Pages**
   - Source: **Deploy from a branch**
   - Branch: **main** / **(root)**
   - Clique em **Save**

7. Aguarde ~1 minuto e acesse:
   `https://SEU_USUARIO.github.io/treino-pwa/`

### Instalar no celular

1. Abra o link acima no Chrome do Android
2. Aparecerá um banner "Instalar" no app, ou use o menu do Chrome → **"Adicionar à tela inicial"**
3. Pronto! O app fica na tela inicial igual a um app nativo e funciona **offline**

## Dados

- Armazenados localmente no celular via **IndexedDB**
- Ninguém acessa seus dados (nem internet é necessária)
- Use **Exportar** (aba Histórico) para fazer backup em .json
- Use **Importar** para restaurar em outro dispositivo

## Funcionalidades

- ✅ Registrar treino (PUSH / PULL / LEGS / UPPER / LOWER)
- ✅ Lançar carga e repetições por série
- ✅ Check-in com observação
- ✅ Calendário com dias treinados
- ✅ Streak de dias consecutivos
- ✅ Gráfico de evolução de carga por exercício
- ✅ Histórico com opção de apagar
- ✅ Exportar / Importar dados (backup .json)
- ✅ Funciona 100% offline
- ✅ Instalável na tela inicial
