# DevBoard

A developer portfolio manager CLI tool to track your projects, skills, and generate portfolio content.

## Features

- Track personal development projects with details like repo URL, demo URL, and dates
- Tag projects with technologies/skills
- Filter and search projects by technology, name, or date
- Export your portfolio as a markdown file
- (Coming soon) Generate a static website to showcase your work

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/yourusername/devboard.git
   cd devboard
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Build the project:
   ```
   npm run build
   ```

4. Link the CLI tool globally:
   ```
   npm link
   ```

## Usage

### Adding a project

```
devboard add
```

Follow the interactive prompts to enter project details.

### Listing projects

```
devboard list
```

Options:
- `-t, --tech <technology>` - Filter by technology
- `-s, --search <term>` - Search in name and description
- `-h, --highlighted` - Show only highlighted projects

### Managing categories

View all technologies used in your projects:
```
devboard technologies
```

### Generating a portfolio markdown file

```
devboard export
```

Options:
- `-f, --file <filepath>` - Output file path (default: portfolio.md)
- `-t, --tech <technology>` - Filter by technology
- `-h, --highlighted` - Include only highlighted projects

### Deleting a project

```
devboard delete
```

## Weekly Growth Plan

### Week 1: Add and list projects via CLI ✅
- Basic project tracking functionality
- Command-line interface for adding and listing projects

### Week 2: Tag projects with technologies
- Ability to tag projects with technologies
- Filter projects by technology

### Week 3: Search/filter projects by tags
- Enhanced search capabilities
- Multiple filter criteria

### Week 4: Export a markdown portfolio file
- Generate markdown files for portfolio content
- Customizable output options

### Week 5: Build a simple web UI
- Basic web frontend to view projects
- Responsive design

### Week 6+: Deploy portfolio to GitHub Pages
- Static site generation
- Deployment automation

## Development

### Running tests

```
npm test
```

### Running in development mode

```
npm run dev
```

## License

MIT
