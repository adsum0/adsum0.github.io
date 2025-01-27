# Jekyll Simple Resume Template

This project is a simple, modern, and fully customizable resume template built with Jekyll. It provides an easy way to create a professional-looking resume that can be hosted anywhere, such as GitHub Pages.

## Features
- Simple and modern design
- Fully customizable
- Social media links with icons
- Easy to add your own avatar and information
- Easy to customize everything header background included
- Can be hosted on GitHub Pages or other platforms

## Getting Started

Follow these steps to get this project running locally on your machine.

### Prerequisites
- [Ruby](https://www.ruby-lang.org/en/documentation/) – Required for Jekyll.
- [Bundler](https://bundler.io/) – Used to manage Ruby dependencies.
- [Jekyll](https://jekyllrb.com/) – Static site generator used in this project.

### Step 1: Download the Project

Clone this repository to your local machine or fork it to your own GitHub account.
```
git clone https://github.com/zer0dayf/jekyll_simple_resume_template.git
```
### Step 2: Install Dependencies
First, check if Ruby is installed on your system:
```
bash ruby -v
```
If Ruby is not installed, follow the instructions on the [Ruby website](https://www.ruby-lang.org/en/documentation/installation/)

Next, install Jekyll:
```
gem install jekyll
```
Check [Jekyll website](https://jekyllrb.com/docs/) for further information or any problem.


Next, install Bundler:
```
gem install bundler
```
Once Bundler is installed, navigate to the project directory and run:
```
bundle install
```

### Step 3: Run Jekyll Locally
After the dependencies are installed, you can build and serve the resume locally. Run the following command (in your path wherever you cloned repository i.e. C:\your_path\jekyll_simple_resume_template): 
```
bundle exec jekyll serve
```
This will start a local server at http://localhost:4000, where you can view your resume template in a browser.

### Step 4: Customize Your Resume

Edit the `_config.yml`   file to update the following details:

- **show_avatar:** Set to `true` to display your profile picture.
- **name:** Your full name.
- **role:** Your current job role or profession.
- **email:** Your contact email.
- **social media links:** Add your social media profiles such as Instagram, LinkedIn, GitHub, etc.
- and **other sections** properly.

### Example Configuration for `_config.yml`

Edit the `_config.yml` file to update the following details:

```yaml
# Profile settings
show_avatar: true  # Set to true if you want your picture visible
name: "John Doe's Resume"  # Your name
role: "Software Developer"  # Your job title
email: "johndoe@example.com"  # Your email address
show_email_as_logo: true  # If you want to show your email as a logo

# Social Media Links
instagram_usr: "https://instagram.com/johndoe"  # Your Instagram account
twitter_usr: "https://twitter.com/johndoe"  # Your Twitter account
linkedin_usr: "https://linkedin.com/in/johndoe"  # Your LinkedIn account
github_usr: "https://github.com/johndoe"  # Your GitHub account
medium_usr: "https://medium.com/@johndoe"  # Your Medium account
hackerrank_usr: "https://hackerrank.com/johndoe"  # Your HackerRank account
```
### Step 5: Deploy Your Resume
Once you’ve made your changes, you can deploy your resume online. Here are some options:

- **GitHub Pages**: Push your project to a GitHub repository and use [GitHub Pages](https://pages.github.com/) to host your site for free.
For more detailed instructions on deploying with GitHub Pages, visit [GitHub Pages Documentation](https://docs.github.com/en/pages).

### Additional Notes:
1. **Installing Jekyll and Bundler**: We installed jekyll and bundler by using `gem install jekyll bundler` command. Then we used the `bundle install` command to install all dependencies. This command installs Jekyll and the required Ruby gems.
2. **Starting the Jekyll Server**: The `bundle exec jekyll serve` command starts a local development server, allowing you to preview the Jekyll site on your local machine.
3. **Configuration**: You can easily update your personal information and social media accounts in the `_config.yml` file.
4. **Deployment**: I offer the option to deploy the site using GitHub Pages, as it is a free web hosting service that works seamlessly with Jekyll projects.



### Important Note:
**You can improve the project**: I added some empty JavaScript files and module directories, so you can improve the code by adding custom functions from scratch and using JavaScript frameworks. There is a hierarchy in the `_saas` folder that you can use to organize and add your functions.
