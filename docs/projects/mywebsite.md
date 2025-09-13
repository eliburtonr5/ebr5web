---
title: My Website
description: Write up about my website build
icon: material/web
---

# My Website

I created this website to post all my tech projects and other professional content. It is created using **Material for MKDocs** python and markdown based website generator, code is stored through a **GitHub Repository**, and the website is deployed through **CloudFlare Worker Pages** using my custom domain.

---

### **Material for MKDocs**

Material for MKDocs is an open source website generator that uses **Python**, **YAML**, and **Markdown** coding languages to create, build, and deploy websites. 
* **Markdown** code is used for creating the content and documentation on the website.
* **YAML** code is used for defining the properties of the website, main website design, and extra plugins/content.
* **Python** code is used to take the Markdown and YAML code and use the contents to build and deploy the website.

---

### **GitHub Repository**

The code used to create the website with **Material for MKDocs** is all stored in a repository named [ebr5web](https://github.com/eliburtonr5/ebr5web), under my account [eliburtonr5](https://github.com/eliburtonr5). GitHub also acts as the source for the deployment of the website through **CloudFlare Worker Pages**.

---

### **CloudFlare Worker Pages**

CloudFlare Worker Pages acts as the deployment medium and website host for this website. 

It does so by linking to my GitHub repo and running the python deployment script for MKDocs inside of CloudFlare itself to build and deploy the site. It then hosts the site publicly using my custom domain name **ebr5.com**. 

In addition, it will also continue to check the GitHub repo for any changes that have been pushed to the main branch and re-build and deploy the website seamlessly on its own.

---

Eli Burton - Sept. 13 2025