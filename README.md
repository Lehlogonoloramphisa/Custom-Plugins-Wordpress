# Custom-Plugins-Wordpress

Custom Registration and Profile Edit Form with Payment Options
Description
This WordPress plugin provides a custom user registration form with payment options, additional fields, profile editing functionality, and conditional bank details for different payment options. It is designed to allow users to register, update their profiles, and manage payment options seamlessly.

Features
Custom Registration Form: Includes fields for personal information, firm details, qualifications, services, experience, and payment options.

Profile Edit Form: Allows users to update their profile information, including profile pictures and cover photos.

Payment Options: Supports multiple payment methods, including debit orders, credit cards, and EFT (Electronic Funds Transfer).

Conditional Fields: Displays bank details fields based on the selected payment option.

User Profile Display: Displays user profiles with cover photos, profile pictures, and detailed information.

Admin View: Administrators can view all registered users with their profile pictures and details.

Installation
Download the plugin files and upload them to the wp-content/plugins/ directory of your WordPress installation.

Activate the plugin through the Plugins menu in WordPress.

Use the provided shortcodes to display the registration form, profile edit form, and user profile on your desired pages.

Shortcodes
[custom_registration_form]: Displays the custom registration form.

[custom_profile_edit_form]: Displays the profile edit form.

[custom_profile_view]: Displays the user profile.

[custom_all_members]: Displays all registered users (admin-only).

Usage
Registration Form: Add the [custom_registration_form] shortcode to a page where you want the registration form to appear.

Profile Edit Form: Add the [custom_profile_edit_form] shortcode to a page where users can edit their profiles.

User Profile: Add the [custom_profile_view] shortcode to a page where users can view their profiles.

All Members View: Add the [custom_all_members] shortcode to a page where administrators can view all registered users.

Customization
Styling: You can customize the form styling by modifying the inline CSS in the plugin files.

Fields: Add or remove fields by editing the form HTML in the crf_display_registration_form and crf_display_profile_edit_form functions.

Payment Options: Modify the payment options and associated logic in the crf_handle_registration_form_submission function.

Requirements
WordPress 5.0 or higher.

PHP 7.0 or higher.

License
This plugin is licensed under the GPL2 license. See the LICENSE file for more details.

