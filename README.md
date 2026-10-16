# udo — instaladores oficiais

Este repositório guarda **apenas os instaladores oficiais do udo** para Windows.
O código-fonte não fica aqui.

## Onde baixar

- **Site oficial (o único):** [useudo.com](https://useudo.com)
- **Instaladores:** na aba [Releases](https://github.com/useudo/udo-releases/releases) deste repositório

Qualquer outro site, link ou arquivo que diga ser o udo **não é oficial**. Não instale.

## Confira o arquivo antes de instalar

Cada versão vem com um `SHA256SUMS.txt`. No PowerShell, na pasta do download:

```powershell
(Get-FileHash .\nome-do-instalador.exe -Algorithm SHA256).Hash.ToLower()
```

O resultado tem de ser **igual** à linha do instalador em `SHA256SUMS.txt`. Se for diferente, apague o arquivo e baixe de novo por [useudo.com](https://useudo.com).
