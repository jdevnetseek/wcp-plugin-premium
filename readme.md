=== Wordpress Comparison Plugin ===
Contributors: netseeknet
Tags: comparison table, comparison table block, compare table, filter table, data table, wordpress table plugin, wordpress table, table, netseeknet
Requires at least: 4.1
Tested up to: 5.8
Stable Tag: 1.8.2.5
Requires PHP: 5.2.4

Ajax-driven Wordpress comparison plugin used for different industries. Create data tables with filter options and customisable visual properties.

== Changelog ==

==1.8.2.7==
1.Update input type width for top rated check box label.

==1.8.2.6==
1.Add the separation option bullet or vertical line on More info Pop up.
2.Update text font-weight on more info page to normal.

==1.8.2.5==
1. Updated the quote request recipients query to only sort the wcp data with emails.

==1.8.2.4==
1. Create email sending function to top rated WCP data (using rating plugin).
2. Send quote request to three random top rated WCP data.

==1.8.2.3==
1. Added checkbox option to quote request form.
2. Added custom checkbox.
3. Added a setting to change the label of Sending option of quote request.
4. Create email sending function to top rated WCP data (using built-in rating).
5. Create AJAX function to trigger the email sending function.

==1.8.2.2==
1. Fixed the top margin of 'Clear Selection' button on the Shortcode generator for mobile view.
2. Set the font-weight of More Info contents to normal.

==1.8.2.1== 
1.Set search limit for Free version to only the latest 10 wcp data.
2.Set hidden fields only for simple fields.
3.Add options for popup button styling.
4.Added title "Request" on enquiry email.
5.Fix filter height when showing more data.
6.Additional setting for enquiry submit button ( Padding, Fontsize and Border radius).

==1.8.2.0==
1.Change the request quote form sending into 3 random emails to ajax function.
2.Fix json response error on gutenberg editor when wcpquote shortcode added.
3.Added reset button on the field groups to display the more info fields by default.
4.Fix hidden fields should hide only on frontend but can change the value on admin.
5.Fix name fields make it serialized array on database and display on the frontend.
6.Fix layout style of the request quotes form make it scrollable.
7.Fix layout of the filter table checkbox.

== 1.8.1.9 ==
1.Create ajax for single send email on tabular and horizontal View.
2.Create validation rule on form input fields jquery.
3.Create wp_ajax hook action to update quotes entries.
4.Added ajax loader image on jquery forms.
5.Register wp_localize_script to register image directory.
6.Change .prop to .attr on filter table for returning selected/checked category.
7.Change php send email 3 random emails to ajax function for popup and default.
8.Add wcp_timestamp metabox on wcp_outbound_clicks post type and update when track wcp_outbound_clicks is enabled.

== 1.8.1.8 ==
1.Add script when success sending sanitize_email.
2.Create media queries for request forms.
3.Added style for single quotes email.
4.Added JS to get post id and use to get email of current wcp data.
5.Added ndf_data_enable_request_form_meta_box to ndf_data post type and included in more information section groups.
6.Added function on ndf_utility_functions.php for the single request email form.

= 1.8.1.7 =
1.Added field_group table ndf_saved_fields table on the database.
2.Created Field Groups tab on the More Info Page Section.
3.Created 3 section as maximum number of anchored tabs .
4.Created template directory inside include folder.
5.Created secttion1.php,section2.php and section3.php template part for the selected section of the field inside template directory.
6.Created option to change and to add field groups on Add More Fields section.
7.Created anchored tab navigation on page and modal more info.
8.Created 2 columns for each field rows.
9.Seperate field sections. 
10.Don't display field if no value.
11.Fix mobile responsive.

== 1.8.1.6 ==
1.Added field_group options in ndf_saved_fields_data table.
2.Created sections 1-3 as field groups.

== 1.8.1.5 ==
= Quotes Form Settings Field =
1.Change form background color.
2.Change text color.
3.Edit form title.
4.Added setting for form title alignment.
5.Added settings for title font size.
6.Added settings for title line height.
7.Added settings for title font weight.
8.Added settings to change form subtitle.
9.Added settings for content alignment.
10.Added setting to change input field width.
11.Added settings to change button text.
12.Added settings to change button Color.
13.Added settings to change button width.
14.Option to show and hide shortcode.

= 1.8.1.4 =
1.Change the table header of request quote form entries .
2.Log status of request data in request quote form entries.

= 1.8.1.3 =
1.update the look of tables on More info settings field.
2.Make the buttons on WCP settings the same blue as the navigation bar.
3.Make 2 columns on more info section  fields tab.
4.Add WCP Tools submenu to copy the shortcode for quote request.
5.Added file "request-quotes-form-settings.php" under wcp-tools-submenu.

= 1.8.1.2 =
= improve Admin UI =
1.added topnav bar on WCP Settings.
2.Update Navigation bar design.

= 1.8.1.1 =
1. Added logo position settings on result table propeties.

= 1.8.1.0 =
= Minor Bug fixes =
1.Update JQuery deprecated functions.
2.Fix filter table not showing on Wordpress 5.7.1.
3.Fix More Info fields redirecting to 404 page.
4.Fix Table results not fitted on the screen when resize.
5.Fix swithching table ( when tabular selected horizontal settings should hide).

= 1.7.2.6 =
1. Update deprecated functions
2. Update jQuery framework js files.

= 1.7.2.5 =
1. Improve category column structure.
2. Update wordpress-SDK to 2.2.3.
3. Update plugin URL.
4. Update compatibility tag to 5.1.
5. Add style fixes for WP 5.1.
6. Fix selected on More Information Button Action field issue.
7. Add Contributors, Tags and Stable Tag.
8. Fix undefined $ error.

= 1.7.2.4 =
1.Add options display settings to Categories 1-5 settings.
2.Integrate Freemius SDK.
3.Add limit to WCP Data when using Free Plan.

= 1.7.2.3 =
1. Update plugin update checker.
2. Update authentication token and branch.

= 1.7.2.2 =
1. Re-structure plugin files.
2. Fix hiding notices to WCP Editor Role.
3. Add index.php to plugin folders.
4. Improve fixing of data results table layout.

= 1.7.2.1 =
1. Improve data results table layout.
2. Fix data results table cell width on mobile.

= 1.7.2.0 =
1. Add More Info button outbound clicks tracking functionality.
2. Fix timestamp value on Outbound Clicks table and meta box. 
3. Fix results table cell min-width on small devices.

= 1.6.2.11 =
1. Add support to Multi Rating form submission in the More Info pop-up.
2. Re-calculate rating rank if rating is deleted (Multi Rating Pro).

= 1.6.2.10 =
1. Make More Info button and generated button full width in Tabular View.

= 1.6.2.9 =
1. Add WCP capabilities to administrator role after account creation (if license is active).

= 1.6.2.8 =
1. Show meta key in More Info Settings > Fields list.
2. Move more info content after enquiry button (tabular).

= 1.6.2.7 =
1. Save More Info's Name field type as serialized array.

= 1.6.2.6 =
1. Update saving and retrieving  of list field type (More Info fields).

= 1.6.2.5 =
1. Fix script in adding WCP Data Editor role in Authors dropdown.

= 1.6.2.4 =
1. Add WCP Data Editor role.
2. Add and remove capabilites to WCP Data Editor role based on license status.
3. Add WCP Date Editor roles to Author options.

= 1.6.2.3 =
1. Improve keyword search form styles.

= 1.6.2.2 =
1. Fix shortcode generator more info field options style.

= 1.6.2.1 =
1. Fix More Info Content bug on Horizontal layout.
2. Add fixes to More Info Fields > Preview Tab.
3. Update generated button styles.
4. Add More Info UI Settings.
5. Improve license checking script.
6. Improve shortcode generator more info field options style.
7. Minor style fixes.

= 1.6.2.0 =
1. Fix bug in adding more info fields to data results table.
2. Fix non-existent $_POST variables.
3. Fix overlapping image (AJAX function).
4. Minor style fixes.

= 1.5.2.17 =
1. Minor style fix.

= 1.5.2.15 =
1. Fix outbound clicks bug.

= 1.5.2.14 =
1. Fix data results table on mobile (tabular).

= 1.5.2.13 =
1. Fix issue on FF (tabular layout).
2. Fix issue on admin license notices.

= 1.5.2.11 =
1. Fix initial and step shortcode attribute value to use in query.

= 1.5.2.10 =
1. Add Rating Rank script support for MR Premium.

= 1.5.2.9 =
1. Add Rating Rank computation.
2. Add Rating option to Query Order By field options.

= 1.5.2.7 =
1. Fix keyword phrase search
2. Enable total count parameter even if no filter is added to shortcode and enable filter limit settings.
3. Fix line-height issue on filter labels.
4. Enable Filter Options Limit settings.

= 1.5.2.6 =
1. Update keyword search ui settings.
2. Update reset button ui settings.
3. Apply new ui settings to visual presets to keyword search and reset buttons.

= 1.5.2.5 =
1. Reposition keyword search form.
2. Add enter key event handler on keyword search form.

= 1.5.2.4 =
1. Add keyword search form ui settings.

= 1.5.2.3 =
1. Fix jQuery noConflict function.

= 1.5.2.2 =
1. Add excerpt field to data results query.
2. Update search button cursor on hover.

= 1.5.2.1 =
1. Fix reset button function.

= 1.5.2.0 =
1. Add Keyword search form and styles.

= 1.4.2.3 =
1. Add jQuery noConflict function.

= 1.4.2.2 =
1. Add WCP Data sorting field.

= 1.4.2.1 =
1. Add admin email as Bcc to enquiry form email.

= 1.4.2.0 =
1. Add Custom Star Rating option.
2. Add Categories 1-5 results (Tabular Layout) table header label settings.
3. Add attribute escaping on more info fields.
3. Add sanitize_email function to recipient email.

= 1.3.2.5 =
1. Fix protocol issue on jquery ui - smoothness theme css enqueue.
2. Add assigning of parent terms on WCP Data post save_post hook.

= 1.3.2.4 =
1. Improve license checking scripts

= 1.3.2.3 =
1. Minor bug fixes

= 1.3.2.2 =
1. Add Outbound Source Tag filtering
2. Fix license check bug (Failed/Interrupted remote check)
3. Minor bug fixes

= 1.3.2.1 =
1. Fix License Manager bugs
2. Fix deleting WCP plugin internal server error bug

= 1.3.2.0 =
1. Fix license page bug.
2. Update caching variables
3. Update shortcode generator
4. Update shortcode attributes
5. Add more info fields as shortcode attributes
6. Add URL filtering of data (Categories 1-5)
7. Fix minor bugs on frontend
8. Fix minor bugs on WCP Settings fields

= 1.2.2.0 =
1. Improve license checking.
2. Add update plugin restriction.
3. Add Outbound Clicks tracking.
4. Add Enquiry Form function.
5. Add Data Result Table Horizontal layout option.
6. Add option to add More Info fields to data results table.
7. Add caching of filters selections.
8. Redirect to license page settings after plugin activation.

= 1.1.2.1 =
1. Minor bug fixes.

= 1.1.2.0 =
1. Update plugin name to Wordpress Comparison Plugin.
2. Update plugin folder name to wordpress-comparison-plugin.
3. Rename main plugin file to wordpress-comparison-plugin.php
4. Add license management script.
5. Update plugin's admin menu labels.
6. Replace UIKit slider with Slick slider.
7. Fix slider nav styles.
8. Add filter option limit.
9. Add Show More/Show Less function.
10. Remove "Featured" tag styles and functions.
11. Add featured query priority to data listings.
12. Update modal width.
13. Fix layout issues.

= 1.0.2.2 =
1. Fix Modal Pop-up logo styles.
2. Fix More Info link font color.
3. Add justify text alignment option on modal UI settings.

= 1.0.2.1 =
1. Tested plugin to Wordpress 4.7.3

= 1.0.2.0 =
1. Beta version.

= 1.0.1.0 =
1. Alpha version.

== Screenshots ==

![Alt text](https://wcp.6bin.com/wp-content/uploads/2021/08/money1-1.png "Optional title")
![Alt text](assets/images/setup_wp_comparison.jpg "Optional Title")
