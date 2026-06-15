Kanban Board Application

Project Setup Instructions

1. Clone the repository:
   
   git clone <repository-url>
cd <project-folder>

2. Install dependencies:
   
   npm install

3. Create a `` file and add your Supabase credentials:
   
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key

4. Run the development server:
   
   npm run dev

5. Open "http://localhost:3000" in your browser.

---

Technologies Used

- Next.js 16
- React
- TypeScript
- Tailwind CSS
- Shadcn UI
- Zustand (State Management)
- Supabase (Authentication & Database)
- React Hook Form
- Yup Validation
- DnD Kit (Drag and Drop)
- Sonner (Toast Notifications)

---

AI Tools Used During Development

ChatGPT

- Authentication flow implementation
- Supabase integration guidance
- State management improvements
- UI/UX suggestions
- Debugging and error resolution
- README documentation assistance

---

Assumptions & Limitations

Assumptions

- Users must register and log in before accessing the Kanban board.
- Each user manages their own boards and tasks.
- Supabase authentication and database services are properly configured.

Limitations

- Real-time collaboration is not implemented.
- File attachments are not supported.
- Board sharing between users is not available.
- Task comments and activity history are not included.
- Offline functionality is not supported.
