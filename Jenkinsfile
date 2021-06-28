@Library('SQASharedLibrary@dev') _
     pipelineForSQA(
     repository: 'SQA-SalesForce',
     branch: params.Branch,
     browser: params['Browser Name'],
     retry: params['Retry Count'],
     testSuitesXmlFiles: params.XML,
     testCases:params['Test Cases'],
     agent: params['Agent'],
     url: params['URL'],
     msteams_channel: params['MS Teams Channel'],
     recipientList: params['Recipient List'],
     run_sonar_analysis: params['Code Quality Check'],
     buildName: params['Release Name'],
     description: params.Description
)