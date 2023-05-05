# Open Source HTML5 Wedding Website

- Demo: <http://www.joshuaanna.com/>
- GITHUB: <joshuaaguilar20.github.io/wedding_2023/>
- Simple wedding website No servers required.
- Website hosted from GH pages
- DNS Setup with Go Daddy <https://dcc.godaddy.com/>
- Form from Form-Spree: <https://formspree.io/>
- Comment Plugin: <https://commento.io/dashboard#modal-close>

# Questions

- issues?

# DNS Setup with GO Daddy: <https://carlosroso.com/gh-pages-with-godaddy-domain/>

1. Set up domain in repo settings
In your repository, go to Settings > Pages > Custom domain. Write your domain without www.

2. Pull changes
Step 1 will add a CNAME file to your deployment branch —e.g. main. Remember to pull those changes in your local: git checkout main && git pull --allow-unrelated-histories.

3. Configure DNS in GoDaddy
3.1 Add an A record
Point your root domain to the GitHub Pages IP. Make sure to look at the updated IPs here. I took 185.199.108.153.

3.2 Add a CNAME record
Point www to your original GitHub pages domain. Do this by adding a CNAME record from www to <username>.github.io.

4. Add verified domain
Add your custom domain to your GitHub account —read acount, not repo. In GitHub, click on your profile > Settings > Pages. Click “Add a domain”.
