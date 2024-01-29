# Selenium Standalone Chrome Debug Service

This repository contains the necessary configuration to deploy a Selenium Standalone Chrome Debug server using Docker, specifically tailored for the Render platform. The service runs in a private environment and can be used for automated browser testing.

## Overview

The setup includes a `Dockerfile` that pulls the latest `selenium/standalone-chrome-debug` image, which contains a Selenium server and a Chrome browser. This setup is particularly useful for automated testing in CI/CD pipelines.