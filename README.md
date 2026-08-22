# LSPosed ET

Fork do [LSPosed](https://github.com/LSPosed/LSPosed) mantido pela **EzequielDevTeam Technology**.

Framework Xposed aprimorado para Android sem necessidade de reflash do sistema, rodando via Zygisk (Magisk) ou Riru.

## Versões suportadas

| Android | Status |
|---------|--------|
| 8.1 - 13 | Suportado |
| 14 - 15 | Suportado |
| **16** | **Suportado** (LSPlant v6.4 + correções próprias) |
| 17 | Planejado — será adicionado quando as ROMs custom e aparelhos estiverem totalmente atualizados |

## Downloads

Todas as versões em [Releases](https://github.com/EzequielDevTeam/LSPosed-Remake/releases).
O updater do módulo consulta automaticamente o `update.json` deste repositório.

## Instalação

1. Instale o zip do módulo (`zygisk-release.zip`) pelo Magisk com Zygisk ativado
2. Reinicie o aparelho
3. O manager (`manager.apk`) pode ser instalado manualmente ou pela notificação

## Diferenças do original

- Suporte ao Android 16 (ART novo via LSPlant atualizado)
- Fix de `IUserManager.getUsers` para API 36
- Identidade própria (LSPosed ET / EzequielDevTeam Technology)
- Updater apontando para este repositório

## Créditos

- [LSPosed](https://github.com/LSPosed/LSPosed) — projeto original
- [LSPlant](https://github.com/LSPosed/LSPlant) — motor de hooks
