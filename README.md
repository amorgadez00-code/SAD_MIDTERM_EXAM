# Student Scholarship Monitoring System

## Requirements
- Supabase project
- Github
- Web browser

## Setup

1. Create a Supabase project.
2. Open SQL Editor.
3. Run supabase/schema.sql.
4. Copy the Project URL and publishable/anon key.
5. Replace the two placeholder constants in index.html.
6. Run index.html using Live Server.
7. Register synthetic Scholar accounts.
8. Sign in to create their profiles.
9. Create a separate staff account.
10. Promote that account using the SQL setup instruction.
11. Assign a scholarship policy to each scholar.
12. Test submission, verification, evaluation, renewal, and history.

## Security
- Never expose the service_role key.
- Do not put passwords in source code.
- Test RLS with separate scholar accounts.
- Keep official Registrar grades outside this system.

## Scope Limitations
This is an examination-sized minimum viable system.
Official Registrar integration, payment processing, SMS, machine learning,
and a full appeal workflow are not included.


