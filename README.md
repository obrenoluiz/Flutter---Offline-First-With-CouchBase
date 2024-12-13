# 🛠️ Flutter - Offline First With CouchBase

Este projeto demonstra como implementar a abordagem **Offline First** em uma aplicação Flutter utilizando o banco de dados **Couchbase Lite**. 

Com esta abordagem, sua aplicação continua funcional mesmo sem conexão com a internet, garantindo que os dados sejam acessíveis e sincronizados automaticamente assim que a conectividade for restaurada.

---

## 🚀 **Recursos Principais**

- **Persistência Local:** Armazena dados localmente no dispositivo utilizando o Couchbase Lite.
- **Sincronização Automática:** Dados sincronizados com o backend via Couchbase Sync Gateway.
- **Gerenciamento de Conflitos:** Solução eficiente para evitar inconsistências durante a sincronização.
- **Interface Moderna:** Design responsivo e amigável seguindo o Material Design.
- **Multi-Plataforma:** Compatível com Android e iOS, aproveitando o poder do Flutter.

---

## 📋 **Pré-requisitos**

Antes de começar, certifique-se de ter:

- [Flutter SDK](https://flutter.dev/docs/get-started/install) instalado.
- Couchbase Lite SDK configurado no projeto Flutter.
- Couchbase Sync Gateway configurado para sincronização (opcional).

---

## ⚙️ **Como Configurar**

### 1. Clone o repositório:
```
git clone https://github.com/obrenoluiz/Flutter-Offline-First-With-CouchBase.git
cd Flutter-Offline-First-With-CouchBase
```

### 2. Instale as dependências do Flutter:
```
flutter pub get
```

### 3. Configure o Couchbase Lite:
- Siga a [documentação oficial](https://docs.couchbase.com/couchbase-lite/current/introduction.html) para adicionar o Couchbase Lite ao seu projeto.

### 4. Configure o Sync Gateway (opcional):
- Certifique-se de que o Sync Gateway está rodando e configurado para seu banco de dados Couchbase Server.

### 5. Execute o projeto:
```
flutter run
```

---

## 🛡️ **Abordagem Offline First**

1. **Inicialização Local:** Todos os dados necessários são carregados do banco de dados local Couchbase Lite.
2. **Sincronização Automática:** Assim que a conexão com a internet é detectada, as alterações são sincronizadas com o backend.
3. **Gestão de Conflitos:** Conflitos de dados são resolvidos automaticamente para garantir consistência.

---

## 🤝 **Contribuição**

Contribuições são bem-vindas! Sinta-se à vontade para abrir uma _issue_ ou enviar um _pull request_.

1. Faça um fork do projeto.
2. Crie uma branch para suas alterações:
   ```
   git checkout -b minha-feature
   ```
3. Faça o commit:
   ```
   git commit -m 'Adiciona minha feature'
   ```
4. Envie suas alterações:
   ```
   git push origin minha-feature
   ```

---

💻 **Projeto desenvolvido durante o curso Alura!**

---

🌟 **Se você gostou deste projeto, deixe uma estrela no repositório!**
