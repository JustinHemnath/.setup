For 404 error when refreshing a page other than the homepage in a netlify site,
create a _redirects file with no extension in the public folder of your CRA and
paste and save the following line in it. 

/* /index.html 200

This will let netlify know to go back to index.html when refreshing a page 
out of the homepage. Configuration only needed when using BrowserRouter from React-router-dom. This step can be bypassed by using HashRouter but it adds a '#' after main URL and is bad for SEO.
