# ReportPortal-Codeception
Specific class to integrate Codeception-based test framework with Report Portal (http://reportportal.io/).

To use agent-php-Codeception:
1) Update your project's composer.json file with next data:

    "require": {
        "reportportal/codeception": "1.0.x-dev"
    },

2) Update codeception.yml file with next data:

extensions:
    enabled:
        - agentPHPCodeception
    config:
        agentPHPCodeception:
            UUID: 07104d6b-45a0-442f-b7ed-a79fa5321123
            host: https://rp.epam.com
            projectName: your_name_personal
            timeZone: .000+00:00
            launchName: test launch name !!!
            launchDescription: test launch description !!!

3) Execute 'composer update' command. 
