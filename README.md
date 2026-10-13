# Kairos: instalador

Este repositório só distribui o **instalador do Kairos**, o aplicativo de produtividade e disparos para Windows. Ele **não contém o código-fonte**.

**Desenvolvido por Matheus Santos. Todos os direitos reservados** (veja o arquivo [LICENSE](LICENSE)).

## Como instalar

1. Na coluna da direita desta página, abra **Releases** e baixe o arquivo `Kairos-Setup.exe` da versão mais nova.
2. Execute o arquivo e siga os passos na tela.
3. O Windows pode mostrar a mensagem **"O Windows protegeu o seu computador"**. Isso acontece porque o instalador ainda não tem assinatura digital (ela é paga). Clique em **Mais informações** e depois em **Executar assim mesmo**.

## Como atualizar

Quando existe uma versão nova, o próprio Kairos avisa, no canto da tela. Você escolhe quando atualizar: **agora**, **depois** ou **amanhã**. Seus dados ficam só no seu computador e **nunca são apagados** ao atualizar. Depois da atualização, o Kairos mostra uma janela com **o que mudou**.

Para o Kairos conferir se há versão nova, ele consulta este repositório pela internet. Só lê o número da versão mais nova e não envia nenhum dado seu. Dá para desligar o aviso em Configurações > Atualizações.

## Conferir o arquivo baixado (opcional)

Cada versão traz, nas notas, o código **SHA-256** do instalador. Para conferir no PowerShell:

```powershell
Get-FileHash .\Kairos-Setup.exe -Algorithm SHA256
```

O resultado precisa ser igual ao das notas da versão.

## Requisitos

Windows 10 ou 11 com o Microsoft Edge (que já vem no Windows).

## Dúvidas

Fale com quem repassou o Kairos para você.