# Github-actions-and-CI-CD-Course-project---YAML

1. Setting up building steps. 
   i) Git actions is the right navigation to yaml workflows.
   <img width="953" height="439" alt="image" src="https://github.com/user-attachments/assets/ae97b6fc-682b-4cfa-b887-d9d073810abe" />
   ii) See that the yaml file is in .github/workflows/main.yml
   <img width="959" height="440" alt="image" src="https://github.com/user-attachments/assets/33f574b2-260e-4622-a8e8-b500dbe31c98" />
   iii) Build job witgh steps illustrated.
   <img width="959" height="439" alt="image" src="https://github.com/user-attachments/assets/3e15bf16-d60d-49b8-9e73-ea9a8cbdb93a" />
   iv) actions/checkout@v4 Checks-out your repository under $GITHUB_WORKSPACE, so your job can access it
      'npm install' installs the dependencies defined in your project's 'package.json' file.
      'npm test' runs the test script defined in your 'package.json'. It's crucial for ensuring that your code works as expected before deployment.
      actions/checkout@v4, npm install, npm test are all illustarted in the image below.
   <img width="956" height="436" alt="image" src="https://github.com/user-attachments/assets/f4ebe558-b522-44ae-9014-f5a737282dc6" />

   
2. Additional concepts with yaml in git actions
   i) Define an environment variable 'CUSTOM_VAR' at the workflow level.
   <img width="944" height="443" alt="image" src="https://github.com/user-attachments/assets/c81895d8-7d10-4814-a52a-c07e9234ea59" />
   ii) Working with secrets
   <img width="899" height="424" alt="image" src="https://github.com/user-attachments/assets/ebfc7dd8-3e25-47ea-a148-e6e3ea4a7a48" />
   iii) Conditional execution
   <img width="943" height="442" alt="image" src="https://github.com/user-attachments/assets/114ddeef-8a0b-44b2-aa4b-98a1bb59792c" />
   iv) Using outputs and inputs between steps
   <img width="934" height="440" alt="image" src="https://github.com/user-attachments/assets/7b0168b9-b8fe-413e-bb95-17491cf9010f" />

   
