```mermaid 
graph TD;
    A[Visit Analysiscenter.veracode.com] --> B[Redirects to web.analysiscenter.veracode.com/login/#/login];
    B --> C[Authenticate with username and password];
    C --> D{Authenticated?};
    D -->|Yes| E[Redirects to https://web.analysiscenter.veracode.com/login/#/landing];
    D -->|No| C;
    E --> F[Menu items: <br> - Start Scanning <br> - Security Labs <br> - API Credentials <br> - Integrations <br> - Documentation <br> - Community];
```
