# Webapp-Azure-Static
We are going to deploy a HTML code file named as index.html to Azure Static Web App


![HTML code file](https://github.com/ssquadri/Webapp-Azure-Static/blob/6865cfa4240b2265b32acde724b2472faf5f1369/Azure%20Webapp/index.html)

Here is a Step-by-Step process for this project

Step 1-Create An Azure Static Web App service (PaaS Service) and make sure to add deployment source as Github , Then allow third party access to your GitHub repo, Also select the framework as HTML and specify the location of index.html on the repo.




![create a Static Webapp.png](https://github.com/ssquadri/Webapp-Azure-Static/blob/6865cfa4240b2265b32acde724b2472faf5f1369/create%20a%20Static%20Webapp.png)




![b](https://github.com/ssquadri/Webapp-Azure-Static/blob/6865cfa4240b2265b32acde724b2472faf5f1369/specify%20the%20deployment%20source.png)




![d](https://github.com/ssquadri/Webapp-Azure-Static/blob/6865cfa4240b2265b32acde724b2472faf5f1369/copy%20the%20HTML%20code%20location%20link%20from%20your%20GitHub%20repo.png)




![c](https://github.com/ssquadri/Webapp-Azure-Static/blob/6865cfa4240b2265b32acde724b2472faf5f1369/specify%20the%20framework%20HTML%20in%20this%20case%20and%20paste%20the%20location%20link.png)




![d](https://github.com/ssquadri/Webapp-Azure-Static/blob/6865cfa4240b2265b32acde724b2472faf5f1369/create%20the%20web%20app.png)


Step 2-Once the webapp is created ,see the default URL of the website , Also in the background CI CD workflow of GitHub is working 



![e](https://github.com/ssquadri/Webapp-Azure-Static/blob/6865cfa4240b2265b32acde724b2472faf5f1369/webapp%20is%20created%20%2C%20see%20the%20website.png)




![f](https://github.com/ssquadri/Webapp-Azure-Static/blob/6865cfa4240b2265b32acde724b2472faf5f1369/our%20website%20in%20prod%20env.png)




![workflow of github](https://github.com/ssquadri/Webapp-Azure-Static/blob/f80ded7a4d4f4a57e241392aff3ba9772b9487a2/github%20CICD%20pipeline%20runs%20and%20our%20HTML%20code%20is%20in%20production%20env.png)




Step 3- Now we made some changes to the original index.html file and made the background color to Pink , Then we commit the file to the main branch and made it to the prod env (this is not how it's done in real time scenarios, Instead we usually make branch) Now lets see if the CI/CD pipleline is working




![htmlcode](https://github.com/ssquadri/Webapp-Azure-Static/blob/f80ded7a4d4f4a57e241392aff3ba9772b9487a2/we%20changed%20code%20and%20made%20background%20color%20pink.png)



Step 4- Now the CI/CD works fine and we can see the github workflows and also the background color has been updated through it.




![cicd](https://github.com/ssquadri/Webapp-Azure-Static/blob/f80ded7a4d4f4a57e241392aff3ba9772b9487a2/pink%20background%20edit%20pushed%20through%20github.png)




![cicc](https://github.com/ssquadri/Webapp-Azure-Static/blob/f80ded7a4d4f4a57e241392aff3ba9772b9487a2/changes%20done%20to%20prod%20env.png)


