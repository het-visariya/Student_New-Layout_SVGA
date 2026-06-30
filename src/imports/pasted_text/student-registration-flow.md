Design a complete student-only web experience for SVGA Book Bank, based on the uploaded MP4 reference flow.

This is a production-ready, student-focused portal design.
Do not design admin pages.
Do not redesign the landing page.
Do not invent new product behavior.
Follow the exact flow and visual language shown in the reference video.

TECH / IMPLEMENTATION CONTEXT
- The final UI should be implementable in Next.js App Router
- JavaScript / JSX only
- Tailwind-friendly layout
- Modern responsive web design
- Bright mode only
- Soft pastel blue / white theme
- Rounded cards, clean spacing, subtle glassmorphism
- Minimal but premium motion

IMPORTANT DESIGN GOAL
The design should feel like one continuous student journey:
Login → Registration → Profile Photo → Payment → Success → Dashboard → Browse Books → My Requests → My Account

Keep every screen visually connected and consistent.
Use the video as the exact source of truth for layout, hierarchy, and section order.

--------------------------------------------------
GLOBAL STYLE SYSTEM
--------------------------------------------------

Visual style:
- Bright pastel blue background
- White cards
- Light cyan accents
- Soft shadows
- Rounded corners
- Very light glassmorphism
- Calm, friendly, student-centric layout
- No dark mode
- No 3D-heavy look
- No crowded pages

Typography:
- Bold headings
- Clean readable body text
- Small subtle helper text
- Strong hierarchy for section titles

Motion:
- Soft fade-up on scroll
- Gentle card hover lift
- Slow sponsor marquee animation
- Subtle floating effect on selected cards
- Smooth transitions between steps
- No over-animation

--------------------------------------------------
SCREEN 1: STUDENT LOGIN
--------------------------------------------------

Create a centered student login / identity verification page exactly like the reference.

Structure:
- Top small SVGA brand icon
- Main title: “Student Login”
- Subtitle: “Enter your Aadhaar number to receive an OTP” or similar short verification instruction
- Main centered verification card

Card content:
- Aadhaar Number input
- Mobile Number input
- Send OTP button
- Small helper cards or feature pills below the form:
  - Free Books
  - Secure OTP
  - ₹500 Deposit

Design requirements:
- Keep the card narrow and centered
- Use a soft pastel background
- Make the button prominent
- Inputs should feel secure and minimal
- Keep the page simple and trustworthy

--------------------------------------------------
SCREEN 2: STUDENT REGISTRATION – PERSONAL DETAILS
--------------------------------------------------

After login, the student enters a multi-step registration flow.

This screen should show the first registration step:
- Step indicator at the top
- Main form card in the center
- Section heading: “Personal Details”

Fields to include:
- Email address
- First name
- Father’s name
- Grandfather’s name
- Surname
- Official surname if different
- Aadhaar number
- Mobile number
- College / institute
- Course / stream
- Standard / year
- Additional information
- Birth date
- Education specification
- Occupation
- Gender and other profile data as shown in the video flow

Design requirements:
- Use a clean two-column form layout where appropriate
- Keep fields grouped logically
- Show required field markers subtly
- Add small helper hints below some fields
- Keep the form inside a large soft white card
- Maintain a centered composition with large whitespace around it

--------------------------------------------------
SCREEN 3: STUDENT REGISTRATION – MORE DETAILS
--------------------------------------------------

Create the next registration step with more academic and profile information.

This step should continue the same registration card and same step indicator.

Fields should reflect the second part of the registration flow:
- College / institute
- Course / stream
- Standard / year
- Additional information
- Birth date
- Education specialization
- Occupation
- Student background details

Design requirements:
- Keep the same card and layout language
- Allow dropdowns/select inputs
- Keep the spacing light and consistent
- Make the page feel like a guided form, not a long wall of inputs

--------------------------------------------------
SCREEN 4: STUDENT REGISTRATION – PROFILE PHOTO
--------------------------------------------------

After the details step, show the profile photo upload screen.

Structure:
- Title: “Student Registration”
- Step indicator with profile photo step active
- Large centered card
- Section heading: “Profile Photo”

Inside the card:
- Circle avatar upload placeholder
- “Choose Photo” button
- File requirements note
- Back button
- Continue button

Design requirements:
- Make the photo upload the visual focus
- Use a large circular avatar placeholder
- Add gentle upload state styling
- Keep the action buttons aligned and easy to understand

--------------------------------------------------
SCREEN 5: PAYMENT MODAL
--------------------------------------------------

Create a centered payment modal overlay.

This appears after registration and before success confirmation.

Modal content:
- Modal title: “Complete Payment”
- Amount visible: ₹500
- Deposit note: “Refundable deposit”
- Payment method tabs or options
- Card payment form fields
- UPI or net banking style options if needed
- Pay button

Design requirements:
- Use a soft dimmed backdrop
- Keep the modal clean and elegant
- Emphasize the refundable ₹500 clearly
- Keep the modal compact but usable
- Make it feel secure and official

--------------------------------------------------
SCREEN 6: PAYMENT SUCCESS MODAL
--------------------------------------------------

After payment completion, show a success modal.

Modal content:
- Green success icon
- Text: “Payment Successful!”
- Short confirmation line about the ₹500 deposit or membership being activated
- Clean confirmation button or automatic transition

Design requirements:
- Keep it minimal
- Do not overdo celebration visuals
- Use soft success green accents
- Make it feel official and trustworthy

--------------------------------------------------
SCREEN 7: STUDENT DASHBOARD
--------------------------------------------------

Create the student dashboard exactly in the style of the video.

This should feel like the central control panel after onboarding.

Top navigation:
- Dashboard
- Browse Books
- My Requests
- Account
- User name / student ID on the right

Main dashboard areas:
1. Welcome banner
   - “Welcome, Student!” style greeting
   - Membership status chip
   - Soft gradient banner

2. Student identity card
   - Student name
   - Student ID
   - Small avatar circle
   - Membership / verification status

3. Quick stats cards
   - Membership status
   - Total issued
   - Currently held
   - Reservations

4. Library QR card
   - Large QR code panel
   - Student details
   - Membership badge
   - Small actions like View Full ID / Download

5. Membership status card
   - Active / inactive state
   - Deposit details
   - Verification state

6. Challan history card
   - Empty or populated states
   - Minimal official styling

7. Quick actions list
   - Browse books
   - View requests
   - My account
   - Return books

Design requirements:
- Keep the layout spacious and calm
- Use card-based dashboard blocks
- Make the QR card a key visual feature
- Use subtle hover motion on cards
- Keep everything easy to scan

--------------------------------------------------
SCREEN 8: BROWSE BOOKS
--------------------------------------------------

Create a book browsing page that matches the video’s layout and behavior.

Structure:
- Page title: “Select Books”
- Subtitle or helper text about building a borrowing request
- Step progress indicator at top
- Search and filters at the top
- Selected books summary
- Book list / recommendations section
- Generate challan button at the bottom

Important sections:
- Search by title / author / keyword
- Course filter
- Available books list
- Selected books list
- Availability tags
- Request count summary
- “Generate Challan” button

Design requirements:
- Use a clean column layout
- Keep the selected books panel visible
- Show availability as soft badges
- Keep the search and filters neat and easy to use
- Add subtle empty states and helper messages

--------------------------------------------------
SCREEN 9: MY REQUESTS
--------------------------------------------------

Create the student requests tracking page.

Structure:
- Page title: “My Requests”
- Subtitle about tracking requests, reservations, and procurement
- Tabs:
  - Book Requests
  - Reservations
  - Procurement
- Filter chips:
  - All
  - Pending
  - Approved
  - Procured
  - Returned
  - Rejected

Each request card should include:
- Request ID
- Date
- Request type
- Status
- Small action buttons such as View Details / Full Challan

Design requirements:
- Keep cards clean and softly elevated
- Use clear status pills
- Show request summary in a compact but readable way
- Include empty states when no requests exist

--------------------------------------------------
SCREEN 10: MY ACCOUNT
--------------------------------------------------

Create the account page as shown in the video.

Sections:
- Personal Information card
- Membership status card
- Library QR / member card
- Currently issued books card
- Account action buttons
- Sign out / profile controls

Design requirements:
- Make the student card and QR visible
- Show official membership status clearly
- Use soft bordered cards and subtle hierarchy
- Keep the page practical and formal

--------------------------------------------------
FLOW CONNECTIONS
--------------------------------------------------

The flow should behave like this:
- Student Login leads to Registration
- Registration has multi-step progression
- Photo upload leads to Payment
- Payment leads to Success modal
- Success leads to Student Dashboard
- Dashboard links to Browse Books, My Requests, and My Account
- Browse Books can lead to challan generation
- My Requests updates request progress
- My Account shows QR, issued books, and membership information

--------------------------------------------------
MICRO-INTERACTIONS
--------------------------------------------------

Add subtle interactions only:
- Soft scroll reveal on sections
- Gentle card lift
- Button hover glow
- Smooth step transitions
- Slow sponsor-style marquee if used
- Light floating effect on one or two cards
- No flashy motion
- No aggressive animation

--------------------------------------------------
OUTPUT EXPECTATION
--------------------------------------------------

Create a polished high-fidelity student portal design system and page flow that matches the uploaded video.

The design must include:
- Student login
- Registration steps
- Profile photo step
- Payment modal
- Success modal
- Dashboard
- Browse books
- My requests
- My account

Keep the structure exact, the flow connected, and the UI ready for implementation in Next.js JavaScript / JSX.