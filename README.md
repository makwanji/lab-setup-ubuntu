# Training Institute Lab Setup on Ubuntu 🏫🐧

## Description

Welcome to the "Training Institute Lab Setup on Ubuntu" GitHub repository! This comprehensive collection of scripts and documentation is designed to simplify and streamline the process of setting up a fully functional training lab environment on Ubuntu-based operating systems. Whether you are a training institute looking to create a hands-on learning environment for your students or an individual seeking to enhance your skills, this repository is your go-to resource for a hassle-free setup. 🚀💻

## Features

1. **Automated Installation Scripts**: Our repository includes carefully crafted scripts that automate the installation of essential software and tools required for a training lab. This saves you time and ensures consistency in your lab setup. ⚙️🤖

2. **Step-by-Step Guides**: Alongside the scripts, we provide detailed step-by-step guides that walk you through the setup process. These guides are beginner-friendly and cover every aspect of the lab environment, from system prerequisites to software installation. 📚📝

3. **Customization Options**: We understand that different training institutes and learners have unique requirements. Our repository is designed to be highly customizable, allowing you to tailor the lab environment to your specific needs. 🛠️🧩

4. **Compatibility**: The scripts and guides in this repository are compatible with a wide range of Ubuntu versions, ensuring flexibility and longevity for your training lab setup. 🔄🔗

5. **Regular Updates**: We are committed to keeping this repository up-to-date with the latest software releases and best practices. You can expect regular updates to enhance your lab experience. 🔄🆕

6. **Community Support**: Join our growing community of users who are passionate about creating effective training labs. Get help, share your experiences, and collaborate with others to improve the lab setup. 🤝🌐

## Getting Started

To get started with setting up your training lab on Ubuntu, simply clone this repository and follow the provided guides. Whether you need a lab for software development, cybersecurity, data science, or any other discipline, we've got you covered. Start your journey towards creating an effective and efficient training environment today! 🚀🔧

```
cd ~/code
git clone https://github.com/makwanji/lab-setup-ubuntu.git
cd lab-setup-ubuntu

# 1st time when you create user
ansible-playbook -i 192.168.2.176, create_user.yml

# run this script after updating IP address in your inventory.ini file
ansible-playbook lab-setup.yml -u ansible -i inventory.ini
```

## Contributions

We welcome contributions from the open-source community. If you have improvements, additional scripts, or suggestions to enhance the training lab setup, please feel free to submit a pull request. Together, we can make this repository even more valuable for training institutes and learners worldwide. 🙌🌍

Empower your training programs and learners with a well-organized and efficient lab environment. Explore our "Training Institute Lab Setup on Ubuntu" repository today! 🎓👩‍💻👨‍💻
