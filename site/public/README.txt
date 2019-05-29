This is where Netlify will build the site, as specified in "netlify.toml".

This file also serves the purpose of making the directory non-empty, or it will not be pushed to GitHub
and Netlify will complain "failed during stage 'building site': Deploy directory 'public' does not exist".