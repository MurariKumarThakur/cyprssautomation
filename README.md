    +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ 
     1. clone the project 
     git clone https://github.com/MurariKumarThakur/cyprssautomation/tree/master
     +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
     2.Install package 
     
       npm install 
     +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
     3.Running the scipt use 
       npm cypress open and select Login.spec.js 
       
          or 
          
       npx cypress run browser --chrome   
      
     +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
     4. Run script in docker 
     
     sudo docker run -it -v $PWD:/e2e -w /e2e cypress/included:6.8.0
     
    ++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++ 
     
