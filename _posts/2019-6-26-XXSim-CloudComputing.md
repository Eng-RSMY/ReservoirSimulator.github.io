---
layout: post
title: XXSim Cloud Computing Manual
---
## Step 1: Host the Eclipse format reservoir simulation model on GitHub; 
A Eclipse format reservoir simulation model is a .data file.
Figure 1 is a model (from the SPE 1 study) that is hosted on GitHub. 
![Host reservoir simulation model with GitHub](https://i.postimg.cc/Y2x2cN3x/githubcase.png "GitHub sample")
Figure 1 Hosting a reservoir simulation model on GitHub

Also copy the URL in the browser address bar for the text input box in Figure 3, for example https://github.com/ReservoirSimulator/Case-BlackOil-Spe1 as shown in Figure 1

## Step 2: Sign in to XXSim Cloud Computing
[XXSim Cloud Computing Url https://xxsimweb.azurewebsites.net/](https://xxsimweb.azurewebsites.net/)

Once you've opened the main page, click on the "Sign In" in the upper right corner to sign in, as shown in Figure 2. ![Hosting reservoir simulation model with GitHub](https://i.postimg.cc/3Rw69V9G/home.png "Home Page")

Figure 2 XXSim Cloud Computing Home Page

## Step 3: Click on the "Cloud Computing" menu

Once you're signed in, click on the menu of "Cloud Computing", and the page is shown in Figure 3. [![computing.png](https://i.postimg.cc/6QQV2XYD/computing.png)](https://postimg.cc/YvJLZJc3)

Figure 3 Cloud Computing Page

Paste the URL of the model copied in step 1 into the text input box on the page, and then click Submit to start the simulation, as shown in Figure 4. [![Submit model and run](https://i.postimg.cc/pLMRLVXL/submit.png)](https://postimg.cc/ppCg0HFw)

Figure 4 Pasting reservoir simulation model address, submiting and starting cloud computing

## Step 4: View and download the results
Once the model is submitted, you will get the feedback page shown in Figure V, and paste the results on the browser address bar for access by pasting [the results Url https://xxsimweb.azurewebsites.net/Home/Result](https://xxsimweb.azurewebsites.net/Home/Result) [![result-Addr.png](https://i.postimg.cc/N0cg0sDx/result-Addr.png)](https://postimg.cc/4YWCLTrK)

Figure 5 Getting a URL to view the results of the computing

Open the URL of the results in the browser, you can see download linkages similar to Figure 6, click any link to download.
Each reservoir simulation model outputs 3 results, suffix LOG (running log), SMSPEC and UNSMRY (can be openned with XXSim's post-processing software or Eclipse's Office software) showing the calculation result curve. [![resultdownload.png](https://i.postimg.cc/TYkx6j5f/resultdownload.png)](https://postimg.cc/gn6QyZKT)

Figure 6 Results Download Link
