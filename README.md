## Test of how to publish and host angular app on github

Use angular-cli-ghpages for publishing
https://www.npmjs.com/package/angular-cli-ghpages

``npm install -g angular-cli-ghpages``

Build  

``ng build --prod --base-href "https://jkristia.github.io/site1-demo/"``

publish  
``ngh --dir dist/site1``  
on Mac  
``sudo ngh --dir dist/site1``

References:  
https://alligator.io/angular/deploying-angular-app-github-pages/  
https://www.youtube.com/watch?v=wElk1W1BJ2o
