# Performance Marketing Lead Control Dashboard

Production Next.js/Vercel rebuild.

## Implemented in this starter
- Production app shell and navigation
- Server-side XLSX/XLS/CSV parsing
- New & Not Connected server-side report processing
- 4QT / Lead Squared CRM resolution
- NRI priority over physical location
- Performance source master
- New / Not Connected summary
- 100-row paginated response
- Shared JSON configuration files
- No customer rows are intentionally logged or permanently stored by the app code

## Next modules to connect
- Mapping Mismatch API
- Agency → CRM Gap API
- Mapping Mail Generator
- Shared Settings editor
- Server-side export
- True persistent report sessions for pagination/filtering without re-uploading

## Deploy
Import this folder into a Git repository and deploy the repository to Vercel.
Vercel will detect Next.js automatically.

Important: the current starter re-processes the uploaded file when Previous/Next is clicked because no temporary report store has been added yet. The next production step should add short-lived object storage / report-session storage so the file is uploaded once and subsequent filters/pages operate on the processed report.
