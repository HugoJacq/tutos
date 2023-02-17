# How to work in jupyter notebook on jean zay

**Update new jupyterhub server**
   - go on a machine recognized by jean-zay (or make a tunnel to cal1 : ```ssh -ND 3128 alberta@ige-meom-cal1.u-ga.fr```)
   - open https://jupyterhub.idris.fr/ in a browser (with proxy parameters set to SOCKS with server name = localhost, port 3128)
   
**Old way of doing it**
 - the official instructions by idris : http://www.idris.fr/jean-zay/pre-post/jean-zay-jupyter-notebook.html
 - instead of launching a browser on cal1 (too much processes and memory use), we will make a tunnel between cal1 and a local machine :
     - on the local machine : 
        - ssh -ND 3128 alberta@ige-meom-cal1.u-ga.fr
        - in the network parameters/advanced/ set up a proxy : SOCKS, server name = localhost, port 3128 or in the browser preferences 
        - open a browser and enter the jean-zay adress : https://jean-zay-srv2.idris.fr and follow the rest of the official instructions
