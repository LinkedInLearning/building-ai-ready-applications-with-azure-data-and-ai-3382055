# Building AI-Ready Applications with Azure Data and AI
This is the repository for the LinkedIn Learning course `Building AI-Ready Applications with Azure Data and AI`. The full course is available from [LinkedIn Learning][lil-course-url].

_See the readme file in the main branch for updated instructions and information._
## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"

## Prerequisites
- [Visual Studio Code](https://code.visualstudio.com/learntocode?) with [mssql extension](https://learn.microsoft.com/en-us/sql/tools/visual-studio-code/sql-server-develop-use-vscode?view=sql-server-ver16)
- [An Azure account with the necessary permissions to create and manage resources.](https://azure.microsoft.com/en-us/pricing/purchase-options/azure-account/)

**Services**
 - [Azure OpenAI instance with a text-embedding-ada-002 deployment and a gpt-4 deployment.](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/create-resource?)
 - An Azure SQL Database

**Key Information Needed**
 - Azure SQL Database Server Name
 - Azure SQL Database Name
 - Azure OpenAI Endpoint Name
 - Azute OpenAI Endpoint Key

## Modules
1. **[Creating to Your Free Azure SQL Database](./docs/1-create-azure-SQL-database.md)**: Get started with your own Azure SQL Database.
2. **[Connecting to Azure SQL Database](./docs/2-connect-azure-sql-db.md)**: Get connected with your Azure SQL Database.
3. **[Creating Embedding, and Storing in SQL Database](./docs/3-create-embeddings-for-relational-data.md)**: Dive into the process of embedding and storing data using SQL.
4. **[Vector Search with Vector Functions](./docs/4-use-sql-vector-functions.md)**: Utilize vector functions for efficient search capabilities.
5. **[Create a Chat Application](./docs/5-create-a-chat-app.md)**: Build an application for searches and talk with your data.


## Acknowledgments
A special thanks to all the contributors and maintainers of this repository, special thanks to [Brian Spendolini](https://www.linkedin.com/in/btspendo/) for the examples.

[0]: # (Replace these placeholder URLs with actual course URLs)

[lil-course-url]: https://www.linkedin.com/learning/
[lil-thumbnail-url]: http://

