# Instructions for Implementing the Sofia Project - Caldas Detail Garage

## Project Objective
Create an integrated solution for Caldas Detail Garage that includes:
1. A new page for the company's new brand.
2. Integration of the new page with the existing e-commerce.
3. Automation of sales and customer service through the Sofia bot.

## Required Features

### 1. New Page for the New Brand
- Create a dedicated page for the new brand.
- Modern design aligned with Caldas de Tel Garage's visual identity.
- Highlight the new brand's products.
- Include information about the new brand and its unique features.

### 2. Integration with Existing E-commerce
- Connect the new page to the existing e-commerce system.
- Ensure the new brand's products are managed by the e-commerce system.
- Synchronize inventory and orders between the new page and the e-commerce.

### 3. Sales Automation with Sofia Bot
- Configure Sofia to:
  - Automatically respond to questions about the new brand's products.
  - Process orders and payments directly through the bot.
  - Generate sales reports and send them to the administrator.
  - Notify customers about order status.

## Project Structure

### Directories and Files
- `presentation/`: Contains the pitch presentation for the client.
  - `index.html`: Main presentation file.
- `src/`: Contains the source code for the Sofia bot and the new page.
  - `bot/`: Code related to the Sofia bot.
  - `ecommerce/`: Code related to the e-commerce and integration with the new page.
  - `new_brand/`: Code for the new brand's page.

### Implementation Tasks

#### 1. Create the New Page
- Create the `src/new_brand/` directory.
- Develop the `index.html` file with the new brand's design.
- Add custom styles in `styles.css`.
- Configure links to the new page on the main site.

#### 2. Integrate with E-commerce
- Add the new brand's products to the existing e-commerce system.
- Configure inventory and order synchronization between the new page and the e-commerce.
- Ensure payments are processed correctly.

#### 3. Configure Sales Automation in Sofia Bot
- Add support for questions about the new brand's products.
- Implement functionality to process orders and payments directly through the bot.
- Configure sales report generation and sending to the administrator.
- Add automatic notifications for customers about order status.

## Next Steps
1. Create the `src/new_brand/` directory and start developing the new page.
2. Configure the integration between the new page and the existing e-commerce.
3. Update the Sofia bot with the sales automation features.
4. Test all implemented features.
5. Deploy all changes to the live site.

---

This document is designed to be read by bots and humans, ensuring that the instructions are clear and deterministic for implementation in the code.

## Deployment

- Production URL: https://pitch-cdg-presentation.netlify.app
- Deployed: 2026-02-06
- Deployed from directory: `presentation/`
- Verification: company name on live site reads "Caldas Detail Garage"