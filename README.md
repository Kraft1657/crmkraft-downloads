# CRM Kraft Desktop

Aplicativo de acesso ao **CRM Kraft** para computadores **Windows 10 e Windows 11 (64 bits)**. O aplicativo utiliza o CRM online e requer conexão com a internet.

Este repositório é **público apenas para distribuição**. O código-fonte do CRM Kraft, os dados de clientes e as configurações internas permanecem no repositório privado.

## Baixar o aplicativo

**Versão experimental:** v0.3.1

1. Abra a página de [Releases](https://github.com/Kraft1657/crmkraft-downloads/releases).
2. Selecione a versão `desktop-v0.3.1` quando estiver disponível.
3. Em **Assets**, escolha o arquivo desejado:

| Arquivo | Utilização |
| --- | --- |
| `CRM-Kraft-Desktop-Setup-0.3.1-x64.exe` | Instalação por usuário no Windows |
| `CRM-Kraft-Desktop-Portable-0.3.1-x64.exe` | Execução portátil, sem instalação convencional |
| `SHA256SUMS.txt` | Verificação da integridade dos arquivos |

> **Atenção:** enquanto os executáveis não estiverem anexados à Release deste repositório, a página de downloads ainda não está pronta. Não tente baixar pelo botão **Code**; ele contém apenas a documentação.

## Instalação e uso

1. Baixe o arquivo `Setup` ou `Portable`.
2. Execute-o no Windows 10/11 (64 bits).
3. Entre com sua conta autorizada no CRM Kraft.
4. Mantenha a conexão com a internet durante o uso.

O aplicativo não substitui as permissões de acesso do CRM. Um usuário precisa continuar autenticado e autorizado para acessar Comercial ou Engenharia.

## Verificação de segurança

A versão 0.3.1 é **experimental e ainda não está assinada digitalmente**. O Windows poderá exibir avisos do SmartScreen. Faça download somente da Release oficial e confira o SHA-256 do executável:

```powershell
Get-FileHash -Algorithm SHA256 ".\CRM-Kraft-Desktop-Portable-0.3.1-x64.exe"
```

Compare o resultado com os valores de [SHA256SUMS.txt](./SHA256SUMS.txt), referentes aos executáveis produzidos na compilação validada do GitHub Actions.

## Versão e limitações

Veja [notas da versão 0.3.1](./RELEASE_NOTES_v0.3.1.md). Antes da distribuição para toda a empresa, teste login, acesso aos setores, downloads, notificações e comportamento da bandeja do Windows.

**O código-fonte do CRM Kraft não é distribuído neste repositório.**
