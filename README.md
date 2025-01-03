# Challenge

* A program has been designed to work on two sets of documents, according to some rules and inputs.

- A directory **updates** contains versions of document content that must be used as the final version
- A directory **originals** can contain versions of document content that may or may not be kept and considered for use as the final version
- A single file lists documents that, were they to be present in **originals**, are either:
  - Ignored from the **originals** directory and hence not kept at all - the file defining this behaviour is called **droplist**
  - Kept from the **originals** directory and hence may be used, if not superseded by a document in **updates** - the file defining this behaviour is called **allowlist**

The program should add documents to a new directory called **finals** so that it only contains documents kept or not dropped from **originals** (depending on the **allowlist**/**droplist** file presence and content) which were not superseded by documents from **updates**, along with all the files from **updates**.

The program expects either **droplist** or **allowlist** to be present when it is run. **originals** and **updates** directories may or may not be empty.

# Your Task
The program is a first version and has been provided to you for some early testing. It has been designed to work with UK style addresses and names of people, where the surnames are used as the filenames.

You have been tasked with doing this and providing some feedback to the developer on the program's current functionality, describing any bugs you find and giving clear and concise steps for reproduction.
