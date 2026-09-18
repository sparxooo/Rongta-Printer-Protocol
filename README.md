# Rongta-Printer-Protocol
My adventure with reversing the protocol for a Rongta F82A printer

## Why
I purchased an F82A A4 thermal printer from an offer on a widely known shopping site. On attempting to print to it from Android, I realised you had to use their proprietary app - there was no support for printing via Androids printer services as their older printers offered. 

## Customer support
I contacted customer support and they basically washed their hands of the ability to print from Android directly, and also refused to offer any SDK for the printer unless I met their minimum order quantity. 
Their app is quite good, except for the fact it does not handle printing from Android directly. You can share web pages and PDFs to the app, but they often do not pull across at all, or they end up causing the app to crash (and requiring a clear of storage to fix). 

## The F82A printer
The printer itself seems like a good quality device, with lots of nice touches (such as paper out support, multiple paper types and detecting the end of the page (single sheets, fan-fold shipping labels with gaps, single sheets with black marks, continuous paper roll (that can be kept inside the device), etc. It's also powered by a battery which was a must for my project.

## Apps 
There are multiple apps offered by the manufacturer, but the only one that works with the F82A appears to be the Chrome extension (which DOES work on Windows, not just ChromeOS and Mac), and the main Android app with the manufacturer name as the app name. The other two (printer system, and Print Service) do not talk to the F82A.

## Aim
My aim is to print directly from any application on Android without having to export to an intermediate format and importing via the manufacturer app. The manufacturer app can be used for pairing or other required options.
