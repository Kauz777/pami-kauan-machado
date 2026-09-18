Aula 03 — JavaScript e TypeScript

Nesta aula foram realizados exercícios básicos de JavaScript e TypeScript, além da configuração do ambiente para compilar e executar arquivos TypeScript pelo PowerShell.

⚙️ Comandos utilizados

cd "C:\Users\Camargo\Desktop\Aula 03\exercícios-ts"
npm install -g ts-node typescript
ts-node --version
tsc --version
npm list -g typescript ts-node
npm uninstall -g ts-node
tsc --ignoreConfig exercicio2.ts
node exercicio2.js

📌 Processo

O arquivo exercicio2.ts é compilado utilizando o TypeScript Compiler (tsc), gerando o arquivo exercicio2.js.

Depois, o arquivo JavaScript é executado utilizando o Node.js:

exercicio2.ts → tsc → exercicio2.js → node → resultado

📚 Conteúdos

* JavaScript
* TypeScript
* Tipagem de variáveis
* Arrays
* Tuplas
* Union Types
* Interfaces