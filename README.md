# How much extra money is it costing local taxpayers for the court failing to meet its own timetables for murder?
## by Joe Mahr/ Chicago Tribune

This is part of a series of data crunching the Chicago Tribune has done on court delays in Cook County. This analysis looks at how much extra it is costing Cook County taxpayers to pay to house murder defendants beyond the two years that the court says is its goal to complete each. 

I've included an R project file (Jail_costs.Rproj) that walks you through the code. There's also rmd and html versions, if you prefer. It may simply be easier to download a zip file of this entire repository and work from your computer. (Side note: I'm a relative Github newbie, so I may be making rookie mistakes in how I upload these files. Apologies in advance.)

### **Getting the data**
This is all explained in the project, rmd and html files, but a quick recap.

The biggest thing is getting the raw data. Github doesn't allow hosting huge datasets -- and these are huge. I've stuggled finding ways to finagle them through Large File Storage. So you'll need to create a folder called raw_data in your working directory, and then put six files in there. You can download all six files from my [Google Drive](https://drive.google.com/drive/folders/11QiBorF_GVX85oHQdmI8pbOkU5wFjOMj?usp=share_link).

### **Preparing/ crunching the data**

Again, there's more detail in the actual project, rmd and html files, but basically the analysis figures out how long someone stayed in jail beyond two years (offering some additional cushion because the court's clock doesn't start ticking until an early-stage hearing called an arraignment, versus the arrest). It gets tricky because there are different costs based on different fiscal years, so all of that has to be plugged into the code. The results are in a Final_data folder, if you'd prefer to just go there and miss all the fun.

### **Questions/ comments?**

Contact Joe Mahr at jmahr@chicagotribune.com


