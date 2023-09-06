
## Documentation - Configuring Local Product Search

This document outlines the necessary steps to configure product search locally for seamless integration into your environment.

## Frontend Configuration

**Step 1: Obtain the Frontend Repository**

- Access the frontend repository at [https://github.com/Acuver-KPL/product-frontend](https://github.com/Acuver-KPL/product-frontend).

**Step 2: Clone the Repository**

- Clone the repository to your local development environment using the following command:

```bash
git clone https://github.com/Acuver-KPL/product-frontend.git
```

**Step 3: Docker Configuration for the User Interface**

- To set up Docker for the user interface (UI) component, follow the instructions below:

  a) **Build Docker Image Locally**

     Build the Docker image in your local environment by executing the appropriate commands provided in the repository's documentation.
    ```
    docker build -t product-search-ui .
    ```
    
    ```
    docker run -p 3000:3000 product-search-ui
    ```


These steps will ensure a seamless setup of the frontend component for product search in your local environment.
