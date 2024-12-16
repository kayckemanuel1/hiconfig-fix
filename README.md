
# FIX: Huawei HiConfig — ”Failed to read the configuration information. Check whether the configuration file format is correct. Thank you.”


[PT-BR]

Se você se deparou com esse erro ao tentar usar o programa HiConfig para configuração de roteadores HUAWEI de maneira massiva e já tentou resolvê-lo sem sucesso, leia isto.

1. Esse erro indica um problema com o arquivo de configuração (template) que você está usando. Certifique-se de que o arquivo está correto e livre de erros. Considere refazê-lo do zero e verifique se há um novo template disponível para download.
2. Evite nomear o arquivo com caracteres especiais, como espaços, hashtags, asteriscos e outros. Para evitar problemas, recomendo salvar o arquivo na pasta raiz do armazenamento ``(C:)``.
3. Embora esse erro geralmente esteja relacionado ao arquivo de configuração, a causa mais frequente pode ser um problema na leitura desse arquivo. *O programa HiConfig utiliza o Microsoft Excel como dependência para ler as informações da planilha*. Portanto, se você não possui o pacote Office 365 ativado, usa uma versão antiga do Excel, utiliza uma versão desatualizada do Windows ou está emulando o programa em outro sistema, é provável que receba esse mesmo erro, o que pode gerar confusão. Assim, recomenda-se usar o Windows 10 ou superior e ativar o pacote Office para garantir o funcionamento do programa.

Se, mesmo após seguir todas essas orientações, o erro persistir, entre em contato com o suporte oficial da Huawei.

[EN-US]

If you encountered this error while trying to use the HiConfig program for mass configuration of HUAWEI routers and have already tried to resolve it without success, read this.

1. This error indicates a problem with the configuration file (template) you are using. Make sure the file is correct and free of bugs. Consider recreating it from scratch and check if a new template is available for download.
2. Avoid naming the file with special characters such as spaces, hashtags, asterisks, and others. To prevent issues, I recommend saving the file in the root folder of your storage ``(C:)``.
3. Although this error is usually related to the configuration file, the most common cause is a problem with reading that file. *The HiConfig program relies on Microsoft Excel as a dependency to read spreadsheet information*. Therefore, if you don’t have the Office 365 package activated, are using an outdated version of Excel, an outdated version of Windows, or are emulating the program on another system, you are likely to encounter the same error, which can be confusing. Thus, it is recommended to use Windows 10 or higher and activate the Office package to ensure the program works correctly.

If, even after following all these guidelines, the error persists, contact Huawei’s official support team.
