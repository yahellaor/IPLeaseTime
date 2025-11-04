# IPLeaseTime
DHCP Lease Time Calculator

Overview

This is a single-page web utility designed to assist network administrators and IT professionals in configuring DHCP servers by providing quick, accurate conversions for IP lease times. Since DHCP servers typically require the lease duration to be specified in seconds, this calculator eliminates manual errors and offers guidance based on network best practices.

The application is built using HTML, Vanilla JavaScript for logic, and styled beautifully with Tailwind CSS for a responsive, modern interface.

Core Functionality

The application serves two main conversion purposes:

1. Convert Human-Readable Time to DHCP Seconds

Easily input time values in Days, Hours, Minutes, and Seconds. The calculator automatically aggregates these inputs to display the total number of seconds required for your DHCP server configuration.

2. Convert DHCP Seconds to Readable Time

Input an existing total lease time value (in seconds) from your server settings to see its equivalent duration broken down into Days, Hours, Minutes, and Seconds in a clear, human-readable format.

Key Features

Best Practice Recommendations: A dedicated panel provides clear, data-driven suggestions for lease times across three common network environments:

High-Turnover Networks (Public Wi-Fi, Hotels): Recommends short lease times (e.g., 30 minutes to 4 hours) to efficiently manage limited IP pools.

Stable Networks (Home, Small Office): Recommends medium lease times (e.g., 24 hours to 7 days) to minimize renewal traffic while maintaining flexibility.

Enterprise/Large Fixed Networks: Recommends long lease times (e.g., 10 to 30 days) for maximum stability.

Critical 0-Second Warning: Includes a prominent, collapsible alert explaining the ambiguity and potential risks of setting the lease time to "0 seconds," strongly advising the use of static IP reservations instead.

Responsive Design: Optimized for use on all devices, from mobile phones to desktop monitors, using Tailwind CSS utilities.

Usage

Simply open the dhcp_lease_calculator.html file in any web browser. No installation or external services are required.
