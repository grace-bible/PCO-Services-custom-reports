# Planning Center PCO Services Custom Reports

These customized plans print to include the exact information needed on a given printout by using HTML, CSS, and Liquid reporting tags.

## Customization

The template provides several customization options to tailor the output according to your needs. These options can be adjusted within the `<!-- CUSTOMIZATION:` section of the code.

### Variables

Here is a list of variables you can define:

- **Notes Categories**

  - `notes_column_1_category`: The category name of notes to print for column 1.
  - `notes_column_2_category`: The category name of notes to print for column 2.
  - `notes_column_3_category`: The category name of notes to print for column 3.

- **Item Styles**

  - `item_styles`: Custom CSS styles for special items, e.g., songs.

- **Specific Positions**

  - `audio_A1`: Position name for Audio FOH.
  - `audio_A2`: Position name for Audio Tech (A2).
  - `producer`: Position name for Producer.
  - `worship_leader`: Position name for Worship Leader.

- **Print Settings**
  - `print_item_description`: Boolean to decide whether to print item descriptions.
  - `force_page_break`: Boolean to decide whether to force a page break for the roster.
  - `print_rehearsal_times`: Boolean to decide whether to print rehearsal times.
  - `print_other_times`: Boolean to decide whether to print other times.
  - `print_plan_people`: Boolean to decide whether to print plan people options.
  - `print_phone`: Boolean to decide whether to print phone numbers of plan people.
  - `all_categories`: Boolean to decide whether to print all categories of plan people.
  - `my_categories`: Array of individual category names of people to print.
  - `categories_to_print`: Array of teams of people to print reports for.
  - `position_to_print`: Specific position to print outside of a team.
  - `notes_categories`: Array of note fields to print with the whole plan.
  - `print_plan_item_times`: Boolean to decide whether to print plan item times.

## Inspiration

Enclosed templates were largely inspired by the iterative `forloop` [from this repo](https://github.com/josephdadams/PlanningCenterServicesReports) that generates a singly printable packet for the entire team at once.

The need for these report templates was driven toward more granular flexibility by the need to operate with a large-scale volunteer team of nearly 70 volunteers and staff for an anniversary gathering of our multisite campuses.

## Contributing

If you have any suggestions or improvements, please submit a pull request or open an issue.

## License

This project is licensed under the MIT License.
