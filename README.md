# NovelKit

A beautiful, feature-rich writing workspace for crafting novels and long-form narratives. NovelKit provides writers with an intuitive interface to manage story structure, characters, worldbuilding, and manuscripts all in one place.

## ✨ Features

### 📚 Novel Management
- Create and manage multiple novels in your workspace
- Store novel metadata including title, genre, and status
- Track novel progress with real-time statistics
- Import/export backups of your entire workspace as JSON

### ✍️ Writing & Chapters
- Dedicated writing mode with a distraction-free editor
- Organize your manuscript into chapters with titles and descriptions
- Track chapter status: Planned, Drafting, or Done
- Live word count tracking for each chapter and overall manuscript
- Quick chapter navigation from the sidebar

### 🎭 Characters
- Create and manage character profiles for your story
- Add detailed character information and descriptions
- Color-coded character avatars for visual organization

### 📖 Plot & Structure
- Build your story's narrative framework using acts
- Organize plot points and story clues
- Plan your story's progression with custom act blocks
- Track important story beats and plot devices

### 🌍 Worldbuilding
- Comprehensive world and setting documentation
- Store lore, history, rules, and aesthetic details of your world
- Create location database with specific place descriptions
- Reference your world details while writing

### 📋 Story Planning
- One-line summary of your novel's premise
- Themes and tone documentation
- Full synopsis for complete story overview
- Target word count and deadline tracking
- General notes and brainstorming space

### 📊 Overview Dashboard
- Real-time statistics showing:
  - Total chapters count
  - Completed chapters
  - Character count
  - Total words written

### 💾 Data Management
- Auto-save to browser's local storage
- Export manuscript as plain text (.txt)
- Export entire workspace as JSON backup (.json)
- Import backups to restore your work
- Drag-and-drop JSON import support

### 🎨 UI Features
- Beautiful dark theme with warm gold accents
- Responsive sidebar navigation
- Modal dialogs for novel creation and settings
- Genre selection (Thriller, Fantasy, Sci-Fi, Mystery, Romance, Historical, Horror, Nonfiction, Adventure/Action, Dystopian)
- Focus mode to hide sidebar and minimize distractions
- Smooth transitions and polished interactions

## 🚀 Getting Started

1. **Open the Application**: Simply open `index.html` in your web browser
2. **Create Your First Novel**: Click the "New novel" button in the sidebar
3. **Choose a Genre**: Select your story's primary genre
4. **Start Writing**: Navigate to the Write tab to begin drafting chapters
5. **Organize Your Story**: Use the other tabs to develop characters, plot, and world

## 📂 File Structure

- `index.html` - Complete standalone application with embedded HTML, CSS, and JavaScript
- `README.md` - Documentation (this file)

## 💡 Usage Tips

### Sidebar Navigation
- **Novels**: List of all your projects; click to switch between them
- **Overview**: Dashboard with statistics and story premise details
- **Write**: Full-screen writing editor with chapter sidebar
- **Chapters**: View and manage all chapters in your manuscript
- **Characters**: Create and organize character profiles
- **Plot**: Develop your story structure with acts and plot points
- **World**: Build and reference your story's setting and lore

### Chapters Tab
- Add new chapters with the "Insert brand new chapter row" button
- Click chapter titles to rename them
- Click status badges (Planned/Drafting/Done) to cycle status
- Use action buttons to edit or delete chapters

### Write Tab
- Select a chapter from the left sidebar to start writing
- Chapter title is at the top with word count tracking
- Status badge allows quick status updates while writing
- All content is saved automatically to local storage

### Export Options
- **Manuscript (.txt)**: Plain text compilation of all chapters for sharing or printing
- **Backup (.json)**: Complete project backup with all data; import anytime to restore

### Focus Mode
- Enable focus mode in the browser to hide UI elements and minimize distractions
- The sidebar will hide, giving you maximum screen space for writing

## 💾 Data Storage

NovelKit stores all your data in your browser's **local storage**. Your novels are never sent to any server. 

**Important**: Clear your browser's local storage or cache may delete your work. Use the export feature regularly to create backups.

## 🎨 Customization

The application uses CSS custom properties for easy theme customization. Edit the `:root` variables in the `<style>` section to change colors:

```css
--bg: #0f0e0c;          /* Background color */
--text: #f0ede8;        /* Primary text color */
--accent: #c9a96e;      /* Accent gold color */
--red: #c06060;         /* Delete/danger color */
--green: #6a9e6a;       /* Done/complete color */
--blue: #6a8eae;        /* Drafting color */
```

## 📱 Browser Compatibility

Works best in modern browsers with ES6 support:
- Chrome/Edge (recommended)
- Firefox
- Safari
- Any Chromium-based browser

## 🎯 Keyboard & Navigation

- **Tab Navigation**: Use the sidebar nav items to switch between views
- **Click Status Badges**: Cycle through chapter/novel statuses
- **Modal Dialogs**: Use keyboard-friendly buttons to submit or cancel

## 📝 Features Detail

### Novel Status States
- **In progress**: Currently working on the manuscript
- **Completed Blueprint**: Story structure is complete
- **Drafting Phase**: Initial draft in progress
- **Editing Workflow**: Revising and editing
- **On Hold**: Project paused

### Chapter Status States
- **Planned**: Chapter outline exists but not written
- **Drafting**: Chapter is being written
- **Done**: Chapter is complete

## 🔒 Privacy

All data is stored locally on your device. NovelKit does not:
- Send data to external servers
- Track your writing
- Require an account or login
- Collect personal information

## 🐛 Troubleshooting

**Lost my work**: If you accidentally cleared browser data, check if you have a JSON backup file. Import it through the "Import Backup" button.

**App not saving**: Ensure your browser allows local storage. Check browser settings and privacy/storage permissions.

**Can't import backup**: Make sure the JSON file was exported from NovelKit. The file structure must match the app's data format.

## 📄 License

Feel free to use, modify, and distribute as needed.

---

**Happy Writing!** 📖✨

Start forging your novel masterpiece today with NovelKit.
