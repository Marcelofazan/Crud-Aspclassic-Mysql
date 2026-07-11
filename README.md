## 🌐 AspClassico-Pessoas
Exemplo de CRUD em ASP Clássico com banco de dados MySQL.

#### 📋 O que você vai encontrar neste projeto
| Tecnologia | Descrição |
|-----------|-----------|
| **ASP Clássico** | Estrutura de processamento que permite executar scripts no lado do servidor (VBScript) |
| **HTML5** | Template Responsivo [owlcarousel](https://owlcarousel2.github.io/OwlCarousel2/demos/demos.html) |
| **Paginação** | Utilização de métodos internos do objeto ADO para lidar com paginação |

#### 💬 Requisitos do Projeto
- Necessário instalar driver MySQL [mysql-connector-odbc-5.3.13-win32](https://dev.mysql.com/blog-archive/mysql-connector-odbc-5-3-13/).
- Necessário Habilitar Aplicativos de 32 Bits no servidor IIS do Windows.
- Para executar a aplicação é necessário executar o Script do MySQL.
  
#### ⚠️ String de conexão do banco
Modifique a string de conexão no arquivo **abreconexao.asp**, no trecho indicado:

```bash
conexao.Open "DRIVER=MySQL ODBC 5.3 Unicode Driver;SERVER=127.0.0.1;PORT=3306;DATABASE=simplesweb;USER=root;PASSWORD=SuaSenha;OPTION=3;SSLMODE=disabled;"
```
O script para criação da tabela do exemplo encontra-se na pasta **Database**.


