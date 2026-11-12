# RABBIANA Student Portal

Live website: https://fazle-rabbi1409.github.io/rabbiana-student-portal/

Students register and sign in with their full name, 10-digit mobile number, and password. New registrations remain pending until an administrator approves them. This password-based setup avoids SMS-provider dependency. A password account does not prove ownership of the phone number; the portal states that to users.

Supabase is used for authentication, shared student records, articles, exam data, server-side exam scoring, results, and private PDF storage. The browser configuration contains only the public publishable key. No service-role secret is included.

The first administrator sign-in details are provided separately to the school owner. Students must contact the administrator if they forget their password.
