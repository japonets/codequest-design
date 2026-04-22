# Guia Básico de Uso de Branches (Git/GitHub)

Este guia tem como objetivo orientar novos integrantes sobre como trabalhar com branches, adicionar seus arquivos e enviar contribuições para a branch principal (`main`).

---

## 1. Clonar o repositório

Caso ainda não tenha o projeto na sua máquina, utilize o comando:

```
git clone <URL_DO_REPOSITORIO>
```

Depois, entre na pasta do projeto:

```
cd <NOME_DO_REPOSITORIO>
```

---

## 2. Criar uma nova branch

Antes de começar a trabalhar, crie uma branch própria para suas alterações:

```
git checkout -b nome-da-sua-branch
```

Exemplo:

```
git checkout -b aula-checkpoints
```

---

## 3. Adicionar seus arquivos/modificações

Faça as alterações necessárias no projeto (código, arquivos, documentos, etc.).

Depois, adicione os arquivos modificados:


```
git add .
```

---

## 4. Fazer o commit das alterações

Registre suas mudanças com uma mensagem clara:

```
git commit -m "Adiciona sistema de checkpoints"
```

---

## 5. Enviar a branch para o repositório remoto

Envie sua branch para o GitHub:

```
git push origin nome-da-sua-branch
```

Exemplo:

```
git push origin aula-checkpoints
```

---

## 6. Criar um Pull Request (PR)

1. Acesse o repositório no GitHub
2. Clique em **"Compare & pull request"**
3. Verifique se:

   * A base é `main`
   * A sua branch está selecionada corretamente
4. Adicione um título e descrição explicando o que foi feito
5. Clique em **"Create pull request"**

---

## 7. Revisão e Merge

Após criar o PR:

* Aguarde a revisão (caso haja)
* Se tudo estiver correto, o PR será aceito (merge) na branch `main`

---

## Boas práticas

* Use nomes de branch descritivos
* Faça commits pequenos e organizados
* Escreva mensagens de commit claras
* Sempre trabalhe na sua própria branch (evite usar a `main` diretamente)

---

## Resumo do fluxo

```
git checkout -b minha-branch
git add .
git commit -m "minhas alterações"
git push origin minha-branch
```

Depois, abra o Pull Request no GitHub.

---

Seguindo esse processo, garantimos organização e evitamos conflitos no projeto.
