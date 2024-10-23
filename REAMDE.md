# John HankBot

### A 3D-printed signature-forging robot

**John HankBot** is a fun project that transforms a standard 3D printer into a signature-forging machine. Inspired by the iconic John Hancock signature, this bot automates the process of signing documents with precision and flair!

## Features

- **Signature Replication**: Uses a 3D printer and a Sharpie to draw famous signatures (or any signature you want!).
- **Easy Customization**: You can modify the bot to work with different markers, signature sizes, and documents.
- **G-code Generation**: Convert any signature into a format that can be read by your 3D printer to automate the signing process.

## Project Inspiration

The name "John HankBot" is a playful nod to the famous John Hancock signature on the U.S. Declaration of Independence. Just as John Hancock made his mark in history, John HankBot will make its mark on paper — one Sharpie stroke at a time.

## Requirements

- **3D Printer** (FDM printers like Prusa, Ender, or any other standard printer with a movable print head)
- **Sharpie (or any marker)** to attach to the print head
- **3D-printed marker holder** (or an alternative method of attaching the Sharpie)
- **Software** for vectorizing signatures and generating G-code (Inkscape, Cura, etc.)

## Setup

1. **Attach the Marker**:
   - 3D print a custom marker holder (files included in the repo) or use tape/zip ties to attach the marker to the printer's print head.
   - Make sure the marker's tip lightly touches the print surface (about 0.1 mm clearance).

2. **Prepare the Signature**:
   - Use software like Inkscape to trace and vectorize a signature image (SVG).
   - Generate G-code using the signature SVG file.

3. **Load the G-code**:
   - Load the generated G-code into your printer’s control software (Cura, PrusaSlicer, etc.).
   - Start the "print" and watch John HankBot sign like a pro!

## Usage

1. **Convert Signatures**: Use your favorite vector tool to create SVGs of any signature.
2. **Fine-Tune**: Adjust the Z-height in your G-code to ensure the Sharpie makes good contact with the paper without dragging.
3. **Enjoy the Signatures**: John HankBot can now sign documents, art pieces, or anything you can imagine.

## Future Plans

- **Multi-marker support**: Automatically swap between multiple markers for different colors or line thicknesses.
- **Document signing automation**: Automate signing entire documents for official or artistic purposes.
- **Signature gallery**: Share and showcase famous signatures forged by John HankBot!

## Disclaimer

This project is meant for entertainment and educational purposes. Please be ethical when using John HankBot. Forging signatures for illegal purposes is a crime.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Happy signing with John HankBot! If you’ve built or modified your own, feel free to share your creations!
