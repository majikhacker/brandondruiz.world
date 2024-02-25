### Creating a Static Site Repository and Pushing to GitHub

1. **Create a Local Repository:**
    mkdir my_project
    cd my_project
2. **Initialize Git Repository:**
    git init
3. **Add Files:**
    touch index.html
4. **Add Files to Staging Area:**
    git add .
5. **Commit Changes:**
    git commit -m "Initial commit"
6. **Create a Repository on GitHub:**
   - Go to GitHub and create a new repository (let's say `my_project`).
7. **Link Local Repository to GitHub:**
    git remote add origin <repository_url>
8. **Push Changes to GitHub:**
    git push -u origin master

### Setting Up Custom Domain and DNS Records

1. **Point Domain to GitHub Pages:**
   - Go to your domain registrar's website and update the DNS settings.
   - Add a `CNAME` record pointing to `<username>.github.io`.
   - Add an `A` record with the GitHub Pages IP address.


In creating my website, I embarked on a journey that involved several key steps. Beginning with
the setup of a repository on my Mac through Bash, I crafted my project's structure, added necessary
files, and committed them to Git before pushing everything to GitHub. Transitioning to website development
, I utilized Hugo to generate a static site. Using GitHub Pages to host my site was really exciting
because it's SSL certified and FREE! Since I paid for my domain on GoDaddy for a dollar and change
for a year, and crafted the HTML/CSS/and .js files myself, I am pretty happy getting my site up and
running for under $5. I configured the custom domain by changing my DNS records on GoDaddy and on
GitHub's side as well. Email integration was also done. I linked my domain to ProtonMail; they are
great when it comes to security and they give you 2 custom domains and let you set up DKIM, MX,
SPF, DMARC, and a catch-all. I enabled HTTPS on GitHub Pages, and then I was finished. It sounds like
a lot more written out, but I will include all of the commands for Bash on Mac and the switches, and
also the DNS/domain information to point it to GitHub. Please check out my personal static website,
and I will be setting up my business website next, but I'll have to host that somewhere else because I
have some backend services/API requests that I have to deal with. So I will be documenting that one
as well. Thanks for reading!

