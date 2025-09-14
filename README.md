# ExServlet - Projeto com Tomcat e Servlet

Este repositório contém um projeto desenvolvido para a disciplina de **Programação Web**, com foco no estudo do **Apache Tomcat** e **Servlets**.

## 📌 Descrição
O objetivo deste projeto foi explorar os conceitos de **Tomcat** e **Servlets**, desde a instalação e configuração do servidor até a criação de um exemplo prático utilizando o **NetBeans** e **Maven**.

## ⚙️ Passos Realizados

1. **Instalação do Tomcat**  
   - O Apache Tomcat foi instalado a partir do link oficial:  
     [https://tomcat.apache.org/download-90.cgi](https://tomcat.apache.org/download-90.cgi)

2. **Criação do Projeto no NetBeans**  
   - Tipo de projeto: `Java with Maven -> Web Application`  
   - Nome do projeto: `ExServlet`  
   - Servidor selecionado: **Apache Tomcat or TomEE**  
   - Versão: **Jakarta EE 11 Web**  
   - Configuração: pasta de instalação do Tomcat + usuário e senha para autenticação

3. **Inicialização do Servidor**  
   - Pelo **NetBeans**: `Services -> Servers -> Tomcat -> Start`

4. **Criação de um Servlet**  
   - Foi criado o servlet **MeuServlet**  
   - Ao rodar a aplicação (`Run`), foi exibida a página padrão do projeto

5. **Ajuste do Plugin Maven**  
   - Para corrigir problemas de execução, foi atualizado o plugin `maven-war-plugin` no `pom.xml` para a versão **3.4.0**:
     ```xml
     <plugin>
       <groupId>org.apache.maven.plugins</groupId>
       <artifactId>maven-war-plugin</artifactId>
       <version>3.4.0</version>
       <configuration>
       </configuration>
     </plugin>
     ```

## 🚀 Tecnologias Utilizadas
- **Java**
- **Jakarta EE 11**
- **Apache Tomcat 9**
- **Maven**
- **NetBeans IDE**

## 👨‍💻 Autor
Projeto desenvolvido como parte das atividades acadêmicas.  
