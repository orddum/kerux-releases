# Kerux: downloads

Aqui ficam os instaladores do **Kerux**, o software de projeção para igrejas da
Orddum, para **Mac** e para **Windows**. Cada versão em [Releases](https://github.com/orddum/kerux-releases/releases)
traz o instalador, o tamanho e o hash SHA-256 do arquivo.

- Site e instalação: https://orddum.com/kerux/
- Política de privacidade: https://orddum.com/kerux/privacidade/

## Mac

Tags `vX.Y.Z` (a release marcada como "Latest"). DMG assinado com Developer ID e
notarizado pela Apple. Requisitos: macOS 14 (Sonoma) ou mais novo, Mac com chip Apple.

Para conferir um arquivo baixado, no Terminal:

```bash
shasum -a 256 ~/Downloads/Kerux-1.2.1.dmg
```

## Windows

Tags `windows-vX.Y.Z`. Instalador `Kerux-X.Y.Z-Setup.exe` para Windows 10 (versão 2004)
ou Windows 11, 64 bits; não precisa instalar mais nada. Ainda sem assinatura de código:
na primeira vez, o Windows pode mostrar "O Windows protegeu o computador" — clique em
**Mais informações › Executar assim mesmo**.

Para conferir um arquivo baixado, no PowerShell:

```powershell
Get-FileHash ~\Downloads\Kerux-1.0.0-Setup.exe -Algorithm SHA256
```

O resultado precisa ser igual ao hash publicado na versão.

O código-fonte do Kerux não está neste repositório. Software da Orddum
Serviços de Tecnologia Ltda.; todos os direitos reservados.
