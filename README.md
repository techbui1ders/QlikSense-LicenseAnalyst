# Qlik Sense License Analyst
A Qlik Sense application to navigate the waters of Qlik Sense Enterprise license pricing.

![Screenshot](https://raw.githubusercontent.com/techbui1lders/QlikSense-LicenseAnalyst/img/perpetuallicense.png)

For further context, this project is referenced in our blog. It should not be used on the basis of an actual quote, it's simply a helper to understand the ballpark costs associated prior to a Qlik Sense license purchase based on publicly available prices.

## Installation

1. Download the QVF file and place it into your default Qlik Sense application folder
2. Open Qlik Sense and if done correctly you'll see the 'TechBuilders License Analyst' application

![Screenshot](https://raw.githubusercontent.com/techbui1lders/QlikSense-LicenseAnalyst/img/licenseanalyst.png)

## Usage

![Alt Text](https://raw.githubusercontent.com/techbui1lders/QlikSense-LicenseAnalyst/img/techbuilders-licenseanalyst.gif)

Once you have the application installed, open the model that interests you first (ie. Perpetual). Before you can see any of the visuals, you have to choose the number of Professional Users (atleast 1) and the number of Analyzer Users (can be 0) and lastly a timeframe that you would like to analyze across.

The timeframe should include all of the years you're interested in. For example, the selections for a 5 year timeframe should be Years 1-5 and not just 5.

![Screenshot](https://raw.githubusercontent.com/techbui1lders/QlikSense-LicenseAnalyst/img/timeframe.png)

Once you see your scenario, you can switch views from Perpetual to Subscription to see the differences.

## Modifying to fit your needs

The application is self contained in that all of the visualizations and calculations are included by default. All of the numbers and calculations can be referenced in the load script of the application if you'd like to tweak it.

## Limitations

1. This application only includes US based pricing for Qlik Sense Enterprise
2. This application has a max of 5k users and a timeframe of 10 years
3. This application doesn't include taxes or accurate partner discounts

## Shameless Plug

TechBuilders is an IT consulting company focused on all things analytics, web, and security. Visit us at www.techbuilders.info