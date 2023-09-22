<!-- @format -->

# Structure

- main.tf: The main configuration file where we define our core infrastructure resources and modules.
- variables.tf: This file contains the definition of input variables used in the main configuration. These variables are used to parameterize our Terraform configuration.
- outputs.tf: The outputs file defines the values or information we want to extract from our infrastructure after it has been created.
- modules/: This directory contains reusable modules that can be used in the main configuration to abstract complex components of the infrastructure.
- .credentials: This file defines the credential information for our AWS account.

## ADV

1. **Modularity**: it allows us to create reusable modules and keep the main configuration clean and concise. This promotes modularity, making it easier to manage and update specific components of our infrastructure.
2. **Clarity and Readability**: Having separate files for variables and outputs provides clarity and improves readability. It's easier to understand the purpose and usage of variables and outputs when they are defined in their own dedicated files.
3. **Maintainability**: As our infrastructure grows, maintaining a well-organized structure becomes crucial.
4. **Scalability**: The file structure makes it easier to scale our infrastructure by adding more resources and modules.
5. **Collaboration**: Having a clear file structure with separate files for variables, outputs, and main configuration enhances collaboration. Team members can focus on specific aspects of the project without interfering with others.
6. **Separation of Concerns**: Each file has a specific purpose (variables, main configuration, and outputs), which adheres to the separation of concerns principle.
7. **Testing and Continuous Integration**: The structured layout facilitates automated testing and integration with CI/CD pipelines. Testing specific modules or configurations becomes easier when they are neatly organized.

`Those files are all empty and that because I want to give just the global view of good structure😊`
