# ML Systems CDT Website
## How to edit
### Data:
All the information in the website is curated in the "data" directory:
- management.yml -> List of directors and managers
- supervisors.yml -> List of potential supervisors
- students.yml -> List of students (and actual supervisors)
- pulbications.yml -> Full details of publications

These files can be edited to add further students etc. Ideally in the long run we would have methods to created these yml from a maintained database.

### Pages:
Markdown (.md) pages can be added to the "content" directory. These will create new pages on the website. Follow the format of existing ones (such are this README.md) if you are not familiar with using markdown.

### Overall configuration:

- "hugo.toml" contains the main overall information for the website and menu structure.
- "data/homepage/yml" contains the main data controlling the text on the homepage.
