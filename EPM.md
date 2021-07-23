# 1. EPM Demo

## Endpoint Least Privilege Demo
- Introduction of Endpoint Least Privilege. [Detail](https://docs.cyberark.com/Product-Doc/OnlineHelp/EPM/Latest/en/Content/Intro/Introduction.htm?Highlight=Least%20Privilege)
- In this demo we show case two demos
  - 1. How end user run applications or change configuration without admin right in the endpoint
  - 2. How EPM elevate approved applications to run without end user having admin right
- [Demo Video](https://cyberark.kiteworks.com/w/A5tbgK4gL4J4Ey01)

## Just in Time Demo
- EPM policies are defined at enterprise level to determine the applications user can access and for what purpose. However, sometimes user need to perform a specific task that requires admin privileges which you don't have. [Detail](https://docs.cyberark.com/Product-Doc/OnlineHelp/EPM/Latest/en/Content/EndUser/AdHocElevationUser.htm?Highlight=just%20in%20time)
- [Demo Video](https://cyberark.kiteworks.com/w/Svb7iCR2yL8E4e6o)

# 2. How to...

## How to setup Step-Up Idaptive Authentication and demo
- You can force users to provide additional credentials before user can launch applications or run applications with elevated privileges, using integration with CyberArk Idaptive. Users can specify these credentials in the Application Launch Alert, Elevate, and Elevate Trusted dialogs that are configured in the Elevate and Trust policies. [Detail](https://docs.cyberark.com/Product-Doc/OnlineHelp/EPM/Latest/en/Content/EPM/Server%20User%20Guide/StepUpAuthentication.htm?Highlight=Step-Up%20Idaptive%20Authentication)
- This demo show cases
- How to configure EPM to require step-up authentication before launching applications or running applications with elevated privileges
- [Demo Video](https://cyberark.kiteworks.com/w/deF7hn22GjJ187qY)

## How to Remove Local Administrators
- This topic describes and show how EPM manages local administrators on endpoint machines removes users and groups from the local administrator group.
  - [For more detail](https://docs.cyberark.com/Product-Doc/OnlineHelp/EPM/Latest/en/Content/EPM/Server%20User%20Guide/ManageLocalAdministrators.htm?Highlight=Least%20Privilege)
- [Demo Video](https://cyberark.kiteworks.com/w/CFVOibiejoOIjVLW)

# 3. EPM Experience Lab

## Catch Me If You Can
- This lab objective is using a real attack to show case how EPM can stop attack in very early stage
- If CPE Partner want to try this lab.
  - 1. You need to have your EPM SaaS Trail Account, [EPM free trail](https://www.cyberark.com/try-buy/endpoint-privilege-manager/)
  - 2. You need to setup your own testing Windows 10 VM OR Request a ready Windows 10 VM from CyberArk team, you can contact your local CyberArk SE to request it
- [The Demo Video and Lab Guide](https://cyberark.kiteworks.com/w/5doGzcmFSx39chJ2)
