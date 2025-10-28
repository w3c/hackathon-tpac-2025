# W3C Hackathon TPAC 2025: Kobe Edition

This repository contains the [website](https://www.w3.org/2025/11/TPAC/hackathon/) code. Closer to the event, it will also include instructions on how to submit your project.

## About the Hackathon

The W3C Hackathon at TPAC 2025 in Kobe is an exciting opportunity for developers, designers, and web enthusiasts to come together and create quick prototypes using web technologies.

Details on the event — including dates, location, and registration information — can be found on the [official event page](https://www.w3.org/2025/11/TPAC/hackathon/).

## Submission instructions

Stay tuned! This section will be updated closer to November 11th, 2025 with how to prepare your hackathon project for voting.

## Contributing to the website

If you’d like to propose changes to the website, fork this repository and submit a pull request to the `main` branch of this repository.

### Local development

The website is built using Jekyll. Follow the [Jekyll installation guide](https://jekyllrb.com/docs/installation/), and make sure you also have [Bundler](https://bundler.io/) installed. Then, follow these steps:

1. Clone your forked repository:

   ```bash
   git clone git@github.com:<your-username>/hackathon-tpac-2025.git
   ```

2. Navigate to the project directory:

   ```bash
   cd hackathon-tpac-2025
   ```

3. Install the required gems:

   ```bash
   bundle install
   ```

4. Start the Jekyll server (w/ live reload, so that the page refreshes automatically on code changes):

   ```bash
   bundle exec jekyll serve --livereload
   ```

5. Open your browser and go to `http://localhost:4000/2025/11/TPAC/hackathon/` to view the website.
