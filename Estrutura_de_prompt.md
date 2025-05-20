# Estrutura basica 

## 👤 Persona
Descreva quem você é e seu papel no projeto.  
**Exemplo:** Sou um desenvolvedor backend júnior trabalhando em um projeto pessoal.

---

## ✅ Tarefa
Diga claramente o que você está tentando fazer.  
**Exemplo:** Quero configurar autenticação JWT usando NestJS.

---

## 🧩 Etapa
Em que parte do processo você está?  
**Exemplo:** Já instalei os pacotes e configurei o módulo, mas ainda não implementei o AuthGuard.

---

## 📦 Contexto
Explique o cenário geral do seu projeto e decisões já tomadas.  
**Exemplo:** Estou usando NestJS com Prisma e PostgreSQL. Preciso proteger algumas rotas com autenticação.

---

## ⛓️ Restrições
Liste quaisquer limitações técnicas ou de negócio.  
**Exemplo:** Não posso usar bibliotecas externas além das oficiais do NestJS.

---

## 🎯 Objetivo
Qual o resultado final esperado?  
**Exemplo:** Ter um endpoint protegido por JWT funcionando corretamente com um AuthGuard customizado.

---

## 📤 Saída Esperada
Descreva como você gostaria que fosse a resposta.  
**Exemplo:** Um exemplo de código completo da configuração do módulo de autenticação, do AuthGuard e do uso em rotas.

---

## 🛠️ Tecnologias
Liste as principais tecnologias envolvidas.  
**Exemplo:**  
- NestJS  
- Prisma  
- PostgreSQL  
- TypeScript  
- Yarn

---

## 🧪 Código / Erros / Trechos relevantes
Inclua trechos de código, erros ou comportamento inesperado.  
```ts
// auth.guard.ts
@Injectable()
export class AuthGuard implements CanActivate {
  // ...
}
