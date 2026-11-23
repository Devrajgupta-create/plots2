PublicLab.org

![Code of Conduct](https://img.shields.io/badge/code-of%20conduct-green.svg) ![Build Status](https://github.com/publiclab/plots2/workflows/tests/badge.svg?branch=main) ![first-timers-only-friendly](https://img.shields.io/badge/first--timers--only-friendly-blue.svg?style=flat-square) ![Join the chat at https://publiclab.org/chat](https://img.shields.io/badge/chat-in%20different%20ways-blue.svg) ![Code Climate](https://codeclimate.com/github/publiclab/plots2/badges/gpa.svg) ![codecov](https://codecov.io/gh/publiclab/plots2/branch/main/graph/badge.svg) ![View performance data on Skylight](https://badges.skylight.io/typical/GZDPChmcfm1Q.svg) ![Newcomers welcome](https://img.shields.io/badge/newcomers-welcome-pink.svg) ![GitHub license](https://img.shields.io/github/license/publiclab/plots2?logo=gpl) ![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)

The plots2 web application is the content management system for the Public Lab research community. It combines a collaborative research blog (called "research notes") with a wiki, enabling people to share knowledge, document environmental research, and work together.

Read more about the data model.

New to Public Lab? You can get started by exploring the project, learning how it works, and finding your first contribution below.

![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)

You can use Gitpod to open a development environment for this repository without having to configure the entire development environment on your own computer.

Originally developed as a Drupal site, Public Lab was rewritten in Ruby on Rails in 2012. The application has continued to evolve while retaining parts of its legacy Drupal data model and database design. See issue #956 for more information.

We ❤️ Open Source and actively participate in programs such as Google Summer of Code (GSoC), Rails Girls Summer of Code (RGSoC), Outreachy, and Google Code-In (GCI).

Getting Started

Welcome to Public Lab! This section introduces the project and explains how to begin contributing, even if you are new to open-source development.

What can you do with plots2?

The platform provides several features that help the Public Lab community collaborate on environmental technology, design, documentation, and community organizing.

Some of its key features include:

A Q&A portal for peer-based problem solving.
A rich-text and Markdown editor.
Wiki editing and revision tracking.
Tagging and topic-based groups and content organization.
Email notification subscriptions for topics and comments.
A search interface built using the Public Lab API.
A user dashboard presenting recent activity.
A privacy-sensitive, Leaflet-based location tagging system and community map.
Technologies Used

plots2 is primarily built using Ruby on Rails and uses several supporting technologies.

Some of the technologies used include:

Ruby: Main programming language.
Ruby on Rails: Web application framework.
JavaScript and React: Interactive frontend functionality.
HTML and CSS: Frontend structure and styling.
SQLite and MySQL: Supported database options.
Redis: Background processing and application functionality.
Yarn and Webpacker: Frontend dependency management and asset compilation.

For version-specific requirements, refer to the project's Gemfile and prerequisites documentation.

Project Structure

Understanding the repository structure can help you find the right files when exploring or contributing to plots2.

Directory	Description
app/	Main Rails application code
app/models/	Application data models
app/controllers/	Request handling and application logic
app/views/	Views and templates
config/	Application configuration
db/	Database schema, migrations, and related files
doc/	Additional project documentation
lib/	Application libraries and custom code
public/	Public static assets
spec/	RSpec tests, where present
test/	Automated tests
How the Application Works

At a high level, plots2 follows the Model-View-Controller (MVC) architecture provided by Ruby on Rails.

Models: Handle application data and database interactions.
Views: Present information to users through the interface.
Controllers: Process incoming requests and coordinate application behavior.
Database: Stores research notes, users, wiki content, and other application data.
Frontend: Uses JavaScript and React for interactive features.

This structure makes it easier for contributors to understand where different types of changes should be made.

Before You Begin

Before setting up the project locally, make sure you have access to the following:

A GitHub account.
Git for cloning and managing the repository.
Ruby and the Ruby version manager required by the project.
Bundler for installing Ruby dependencies.
Node.js and Yarn for frontend dependencies.
SQLite3 or MySQL for database setup.
Redis where required by the application.

New contributors: You do not need to be familiar with every technology before getting started. Follow the installation instructions step by step and refer to the resources below whenever you need help.

Useful learning resources:

Git documentation
GitHub documentation
Ruby documentation
Ruby on Rails Guides
Node.js documentation
Yarn documentation
Roadmap

We are developing a draft Roadmap for plots2 and our broader Public Lab code projects; read more and comment here.

A full description of the features, audiences, inter-relationships, and goals of Public Lab software projects can be found here:

https://publiclab.org/software-overview

Table of Contents
Getting Started
What can you do with plots2?
Technologies Used
Project Structure
How the Application Works
Before You Begin
What Makes This Project Different
Data Model
Contributing
Prerequisites
Installation
Standard Installation
Windows Installation
Windows Subsystem for Linux 2 Installation
Redis Installation
SSL in Development
Login
Testing
Maintainers
How to Start and Modify Cron Jobs
Bundle Exec
Reply-by-email
Bugs and Support
Recaptcha
Internationalization
Security
Developers
First Time?
Hacktoberfest
What Makes This Project Different

The people who create our platform make very different design and technology decisions from other projects. This stems from our deep belief that, to see a change in the world, we must build and maintain systems that reflect our values and principles.

From design to system architecture to basic vocabulary and communication patterns, our systems have grown organically since 2010 to support a powerful, diverse, and cooperative network of people capable of taking on environmental problems that affect communities globally.

The platform reflects input from people facing serious health issues, on-the-ground organizers, policy specialists, hardware hackers, educators, and civil servants.

This broad community and the Public Lab team have facilitated a space where we can discuss, break down, construct, prototype, and critique real-world projects. Together we have shaped a platform that incorporates familiar pieces but ultimately looks and feels quite different from anything else on the internet.

Despite the growth of our platform, it remains committed to hearing the voices of others, mutual respect and support, an awareness of the barriers and challenges presented by gaps in expertise and knowledge, and a sensitivity to the inequalities and power imbalances perpetuated by many mainstream modes of knowledge production and technological and scientific development.

Our mutual aim to democratize inexpensive and accessible do-it-yourself techniques has allowed us to create a collaborative network of practitioners who actively re-imagine the human relationship with the environment.

Data Model

!Diagram

(Above: draft of our Data model)

Contributing

We welcome contributions from everyone, especially people making their first contribution to open source.

You can contribute by:

Fixing bugs.
Improving documentation.
Adding or improving features.
Writing or updating tests.
Reporting issues.
Helping other community members.

We especially welcome contributions from people belonging to groups underrepresented in free and open-source software.

Contribution Workflow

If you are new to contributing, the following workflow will help you understand how contributions are made.

1. Find an issue

Browse the plots2 GitHub issues and look for issues labelled help-wanted or beginner-friendly tasks.

2. Discuss your idea

Before beginning substantial work, comment on the issue and explain what you would like to work on. This gives maintainers and other contributors an opportunity to provide feedback and helps prevent duplicate work.

3. Fork the repository

Create your own copy of the repository using the Fork button on GitHub.

4. Make your changes

Create a branch in your fork and make changes related to the issue. Keep your changes focused and follow the existing project conventions.

5. Test your changes

Run the relevant tests and check that your changes work as expected.

6. Open a Pull Request

Submit a Pull Request against the main branch of the original repository. Explain what you changed, why the changes are useful, and reference the related issue.

7. Respond to feedback

Maintainers may request changes or ask questions. Respond to feedback and update your Pull Request when necessary.

For detailed instructions, read CONTRIBUTING.md.

Code of Conduct

Please read and abide by our Code of Conduct; our community aspires to be a respectful place both during online and in-person interactions.

Prerequisites

For installation, prerequisites include SQLite3 and RVM.

Click here for the complete list of prerequisites and installation instructions.

Please check the project's required Ruby version before installing dependencies.

Installation

There are multiple ways to explore and run plots2. New contributors can use Gitpod to open a cloud development environment.

For local development, follow the instructions below.

Standard Installation
Fork our repository from https://github.com/publiclab/plots2.
In your terminal, download a copy of your forked repository:
bash
git clone https://github.com/your_username/plots2.git


Replace your_username with your GitHub username.

Enter the new plots2 directory:
bash
cd plots2

Set the upstream remote to the original repository so Git knows where to fetch future updates:
bash
git remote add upstream https://github.com/publiclab/plots2.git

Install Ruby dependencies.

You may need to install the Ruby version specified by the project. If you receive an error such as Your Ruby version is 2.x.x, but your Gemfile specified 2.7.3, install the required Ruby version using RVM or rbenv.

Using RVM:

bash
rvm install 2.7.3
rvm use 2.7.3


Using rbenv:

bash
rbenv install 2.7.3
rbenv local 2.7.3


Configure Bundler to exclude production-only dependencies:

bash
bundle config set without 'production mysql'


Install gems from the Rails root directory:

bash
bundle install

Copy the example database schema:
bash
cp db/schema.rb.example db/schema.rb

Choose your database.

We recommend SQLite3 for local development because some contributors have reported issues using MySQL2.

For MySQL2:

bash
cp config/database.yml.mysql.example config/database.yml


For SQLite3:

bash
cp config/database.yml.sqlite.example config/database.yml


Note: Some tests may fail when using SQLite3 because parts of the project were originally configured for MySQL. These failures do not necessarily indicate that your development environment is incorrectly configured.

Set up the database:
bash
rake db:setup

Install frontend dependencies:
bash
yarn install

Set up React and Webpacker:
bash
rails webpacker:install
rails webpacker:install:react
rails generate react:install


If you are prompted to overwrite existing files, choose no unless you specifically intend to replace them.

For local SSL development, see SSL in Development.

Start the server:
bash
passenger start


Open your browser and navigate to:

http://localhost:3000/

Once the application is running, you can log in using the local development test accounts described in the Login section.
Run the tests to check your installation:
bash
rails test


You can also run system tests:

bash
rails test:system


Some tests may fail when using SQLite3 due to existing database-specific differences. Refer to the Testing documentation for more information.

Windows Installation

We recommend using a virtual environment or a dual-boot system to avoid dependency issues, as Unix-based systems generally work more smoothly with Ruby and Rails development.

Available options include:

Windows Subsystem for Linux (recommended).
Dual booting Ubuntu and Windows.
Setting up a Linux virtual environment.
Windows Subsystem for Linux 2 Installation

Before continuing with the installation steps in this README, WSL 2 users should open the WSL 2 terminal and run the following commands.

Install dependencies required for Ruby:
bash
sudo apt update
sudo apt install curl g++ gcc autoconf automake bison libc6-dev
sudo apt install libffi-dev libgdbm-dev libncurses5-dev libsqlite3-dev libtool
sudo apt install libyaml-dev make pkg-config sqlite3 zlib1g-dev libgmp-dev
sudo apt install libreadline-dev libssl-dev

Install GnuPG and configure RVM:
bash
sudo apt install gnupg2


Retrieve the RVM signing keys:

bash
gpg2 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB


Install RVM:

bash
curl -sSL https://get.rvm.io | bash -s stable

Load the RVM environment:
bash
source ~/.rvm/scripts/rvm

Install and use the Ruby version required by the project:
bash
rvm install ruby-x.x.x
rvm --default use ruby-x.x.x


Replace x.x.x with the Ruby version specified by the project.

For further reference, see the Ruby installation guide for Ubuntu.
Redis Installation

Public Lab uses Redis, which may be required for some application functionality when running the project locally.

Install Redis if you have not already.

Using macOS:

bash
brew install redis


Using Linux:

bash
sudo yum -y install redis


Using Ubuntu WSL2:

bash
sudo apt update
sudo apt upgrade
sudo apt install redis-server


Start Redis:

bash
sudo service redis-server start


Open the Redis CLI:

bash
redis-cli


Test the connection by running:

bash
ping


A successful response should be:

text
PONG


Exit the Redis CLI:

bash
quit

Start the Redis server.

Using macOS:

bash
brew services start redis


Using Linux:

bash
redis-server

Start Sidekiq:
bash
bundle exec sidekiq

If Sidekiq starts successfully, Redis is configured and working.
SSL in Development

At Public Lab, we use the OpenSSL gem to provide SSL (Secure Sockets Layer) for secure HTTPS connections in development mode.

You can run an HTTPS connection on localhost using the following steps:

Start the server with SSL:
bash
passenger start --ssl --ssl-certificate config/localhost.crt --ssl-certificate-key config/localhost.key --ssl-port 3001

Open:

https://localhost:3001

If your browser displays a certificate warning, review the development certificate configuration before proceeding.

You can also use HTTP on port 3000:

http://localhost:3000

HTTPS on port 3001 is useful for functionality such as OAuth authentication that requires a secure connection.

Login

After completing the installation, you can use the following test accounts in your local development and testing environment.

Usernames: admin, moderator, or user

Password: password

These are local development test credentials. Do not use them on production websites or expose them in public deployments.

For more information about login systems, see the Login Systems documentation.

Testing

Testing helps ensure that changes do not introduce unexpected problems.

Run the main test suite:

bash
rails test


For system tests:

bash
rails test:system


For comprehensive instructions, see:

Testing documentation
System tests

When contributing, run the tests relevant to your changes before opening a Pull Request.

Maintainers

See doc/MAINTAINERS.md for Public Lab's policy on feature maintainers.

How to Start and Modify Cron Jobs
We use the Whenever gem to schedule cron jobs.
Cron jobs are written using Ruby syntax and can be found in config/schedule.rb.
Open config/schedule.rb to create or modify cron jobs.
After updating the schedule, run:
bash
whenever --update-crontab

To see the installed cron jobs, run:
bash
crontab -l

For more information, visit the Whenever repository.
Bundle Exec

For some environments, it may be necessary to prepend gem-related commands with bundle exec.

For
