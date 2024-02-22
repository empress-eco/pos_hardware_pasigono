

<div align="center">

<img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Logo" width="80" height="80">


# POS Hardware Pasigono: Retail POS Enhancement

Welcome to the POS Hardware Pasigono project. This application integrates essential hardware capabilities into your existing Point of Sale (POS) system to accelerate retail operations, making them efficient and stress-free.

</div>


## About The Project

POS Hardware Pasigono is a custom application tailored for retailers seeking to streamline POS processes by integrating crucial hardware functionalities. The application offers the following features:

- Weigh scale integration for precise item weight calculation
- Stripe Terminal integration for seamless card payment acceptance
- Direct printing via QZ Tray for instant receipt printing and cash drawer control

## Key Features

- **Weigh Scale Integration:** Connects a digital weight scale to your POS terminal for accurate item weight measurement.
- **Stripe Terminal Integration:** Allows direct card payments within the POS system.
- **Direct Printing via QZ Tray:** Bypasses the print preview screen and prints directly to printers using ESC/POS commands.

For project documentation, please visit [Empress Docs](https://grow.empress.eco/). To report a bug or request a feature, kindly use this [link](https://github.com/empress-eco/pos_hardware_pasigono/issues).

## Technical Stack and Setup Instructions

The application is built using Framework and can be integrated with Empress POS. The installation process is straightforward and can be done from your bench directory using the following commands:

```sh
bench get-app https://github.com/empress-eco/pos_hardware_pasigono.git
bench --site site.name install-app pasigono
```

For weigh scale integration, the digital weight scale must physically connect to the POS terminal (typically via USB or DB9).

For Stripe Terminal integration, a Stripe Terminal and a Stripe account are necessary.

For direct printing and cash drawer control, [QZ Tray](https://qz.io/) needs to be installed on your POS terminal computer.

## Usage

After installing the application, enable the new features in the POS Profile. Once enabled, the weigh scale, Stripe Terminal, and direct printing functionalities can be used in your POS operations. 

## Contributing

We welcome contributions! Here's how you can contribute:

- Fork the Project
- Create your Feature Branch (git checkout -b feature/AmazingFeature)
- Commit your Changes (git commit -m 'Add some AmazingFeature')
- Push to the Branch (git push origin feature/AmazingFeature)
- Open a Pull Request

Refer to the [original project](https://github.com/empress-eco/pos_hardware_pasigono.git) for additional details.

## License and Acknowledgements

This project is under the MIT License. Your contributions are also licensed under the MIT License.

Special thanks to the Empress Community, the architects behind the essential tools that power this project. Their innovation and dedication have been instrumental in building the foundations and functionalities we rely on. We are profoundly grateful for their pioneering work and ongoing support.

Thank you to Aisenyi Malisa for his significant contributions to the creation of this application.

## Notes

Some features may not work universally on all hardware. Specifics for each feature are listed in the respective sections. Also, this application has been tested and is working with specific versions of Empress. 

## Project Links

- Project Repository: [Empress Github](https://github.com/empress-eco/pos_hardware_pasigono)
- Clone Repository: [Github Clone Repo](https://github.com/empress-eco/pos_hardware_pasigono.git)
- Report a Bug or Request a Feature: [Github Issues](https://github.com/empress-eco/pos_hardware_pasigono/issues)