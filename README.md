# Userpoints Transfer

A Backdrop CMS module that allows authenticated users to transfer Userpoints to other users via a configurable block.

## Features
- Transfer points to other users with a simple form.
- Add an optional personal message to each transfer.
- Admin-configurable category and transaction type for transfers.
- Robust validation (minimum 10 points, sufficient balance, etc.).
- Compatible with the Userpoints module.

## Requirements
- Backdrop CMS 1.x
- Userpoints module (required dependency)

## Installation
1. Download this module and place it in your `modules` directory (e.g., `modules/userpoints_transfer`).
2. Enable the module at `admin/modules`.
3. Assign the "Transfer points to other users" permission to desired roles at `admin/people/permissions`.
4. Place the "Points Transfer" block in a region at `admin/structure/block`.
5. (Optional) Configure transfer settings at `admin/config/people/userpoints/transfer-settings`.

## Configuration
- **Category**: Choose a Userpoints category for recording transfers (default: Uncategorized).
- **Transaction Type**: Select a Userpoints transaction type (default: userpoints).
- Settings are saved automatically and applied to all transfers.

## Usage
- Users with the "Transfer points to other users" permission can access the block.
- Enter the recipient's username, the amount (minimum 10), and an optional message.
- Submit to transfer points; the transaction will be logged with the configured category and type.

## License
This module is licensed under the [GNU General Public License v2.0](LICENSE).

## Contributing
Feel free to submit issues or pull requests on GitHub! Contributions are welcome.

## Credits
Developed by willow-fp
