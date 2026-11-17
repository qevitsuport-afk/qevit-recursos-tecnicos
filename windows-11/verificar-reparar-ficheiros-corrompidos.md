
# Como verificar e reparar ficheiros do sistema no Windows 11

Quando o Windows apresenta erros ou comportamentos anormais, alguns ficheiros do sistema podem estar danificados. Podemos utilizar duas ferramentas integradas: DISM e SFC.

## 1. Abrir o Terminal como administrador

1. Clica com o botão direito no menu Iniciar.
2. Selecciona Terminal (Administrador).
3. Confirma a autorização, se solicitada.

## 2. Executar o DISM

Copia e executa:

```cmd
DISM /Online /Cleanup-Image /RestoreHealth
```

Aguarda até o processo terminar. Uma ligação à Internet pode ser necessária para obter ficheiros de reparação através do Windows Update.

## 3. Executar o SFC

Depois de o DISM terminar, executa:

```cmd
sfc /scannow
```

Aguarda pela conclusão da verificação.

O SFC procura ficheiros protegidos do Windows danificados e tenta repará-los.

## 4. Reiniciar o computador

Quando os dois processos terminarem:

1. Reinicia o computador.
2. Testa novamente o Windows.
3. Verifica se o problema inicial foi resolvido.

## 5. Atenção

Estes comandos não resolvem necessariamente problemas de hardware, falhas do disco, malware ou todos os erros do Windows.

Faz sempre uma cópia de segurança dos teus dados importantes.

## Assistência técnica

A QEVIT SUPORT presta serviços de diagnóstico e suporte informático em Angola.

- Website: https://qevitsuport.blogspot.com/
- WhatsApp: https://wa.me/244955801690

**QEVIT SUPORT — Tecnologia que funciona para si.**
