<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/5/5dd1581b5b53bbaaf9d990c90253fb54ef153ac0.png" alt="Project Logo" height="75px">
  <h1 align="center">Empress Active Users</h1>
  <p align="center">
    A robust plugin offering real-time tracking of team activity, designed to empower project managers and team leads.
    <br />
    <a href="https://grow.empress.eco/">Explore the Docs</a>
    ·
    <a href="https://github.com/empress-eco/active_users/issues">Report Bug</a>
    ·
    <a href="https://github.com/empress-eco/active_users/issues">Request Feature</a>
  </p>
</div>

## About The Project

### 📖 Overview

Empress Active Users is an impactful plugin offering real-time tracking of your team's activity. Designed with project managers and team leads in mind, this plugin provides a list of currently active users, empowering you to better manage your resources and stay informed about your project's progress.

### 🌟 Key Features

- Real-time list of active users
- Adjustable refresh interval
- Customizable visibility settings for different roles and users

## Technical Stack and Setup Instructions

### Prerequisites

- A running instance of Empress v13.0.0 or higher

### Installation

Get started with Empress Active Users by following these simple steps:

```sh
# Navigate to bench directory
cd ~/Empress-bench

# Clone the plugin from Github (Required only once)
bench get-app https://github.com/empress-eco/active_users.git

# Build the plugin (Required only once)
bench build --app active_users

# Install the plugin on a specific site
bench --site [your_site_name] install-app active_users

```
Remember to replace `[your_site_name]` with the name of your site in all commands.

## Usage

1. Navigate to **Active Users Settings**
2. Check the **Is Enabled** box and set your desired **Refresh Interval**
3. Select the **Roles** and **Users** for whom you want the plugin to be visible or hidden.

## Contribution Guidelines

We welcome and value your contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
- Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
- Push to the Branch (`git push origin feature/AmazingFeature`)
- Open a Pull Request

## License and Acknowledgments

### License

This project is licensed under the MIT License. Your contributions are also licensed under the MIT License.

### Acknowledgments

Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.

We also wish to acknowledge [Monolith Online](https://github.com/monolithon) for their testing and debugging efforts.

For any issues or queries, reach out to us via our [support](https://grow.empress.eco/) page.
