<!-- # Healthcare Management System

A modern healthcare patient management application built with Next.js that enables patients to register, book, and manage appointments with doctors. Features administrative tools for scheduling, confirming, and canceling appointments with SMS notifications.

## 🔋 Key Features

- **Patient Registration**: Create personal patient profiles
- **Appointment Booking**: Schedule appointments with preferred doctors
- **Admin Dashboard**: Manage and oversee all appointments 
- **Appointment Management**: Confirm, schedule and cancel appointments
- **SMS Notifications**: Automated SMS alerts for appointment confirmations
- **File Management**: Secure file uploads using Appwrite Storage
- **Performance Monitoring**: Track application performance with Sentry
- **Fully Responsive**: Works seamlessly across all devices

## ⚙️ Tech Stack

- **Frontend**: Next.js, TypeScript, TailwindCSS, ShadCN
- **Backend**: Appwrite
- **Notifications**: Twilio
- **Monitoring**: Sentry

## 🚀 Getting Started

1. **Clone the repository**
```bash
git clone [repository-url]
cd healthcare
```

2. **Install dependencies**
```bash
npm install
```

3. **Environment Setup**
Create `.env.local` file with:
```env
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```

4. **Run Development Server**
```bash
npm run dev
```

Visit http://localhost:3000 to view the application.

## 🎨 Styling

The project uses TailwindCSS with custom utilities:

- Custom color scheme
- Responsive typography classes
- Reusable component styles
- Custom animations
- Shadcn UI component overrides

## 📱 Responsive Design

- Mobile-first approach
- Adaptive layouts
- Dynamic sidebar behavior
- Optimized for all screen sizes

## 🔒 Security Features

- Secure file storage with Appwrite
- Protected admin routes
- Consent management
- Secure patient data handling

## 🛠️ Project Structure

```
healthcare/
├── app/
│   ├── admin/
│   ├── patients/
│   └── api/
├── components/
├── constants/
├── lib/
├── public/
└── types/
```


 -->



# Healthcare Management System

A simple healthcare app built with Next.js. Patients can register, book, and manage appointments with doctors. Admins can schedule, confirm, and cancel appointments. SMS notifications are sent for updates.

---

## Key Features

- Patient registration
- Book and manage appointments
- Admin dashboard for appointments
- SMS notifications
- Secure file uploads
- Performance monitoring
- Fully responsive design

---

## Tech Stack

- **Frontend:** Next.js, TypeScript, TailwindCSS, ShadCN
- **Backend:** Appwrite
- **Notifications:** Twilio
- **Monitoring:** Sentry

---

## Getting Started

1. **Clone the repository**

    ```bash
    git clone [repository-url]
    cd healthcare
    ```

2. **Install dependencies**

    ```bash
    npm install
    ```

3. **Set up environment**

    Create a `.env.local` file:

    ```env
    NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
    PROJECT_ID=
    API_KEY=
    DATABASE_ID=
    PATIENT_COLLECTION_ID=
    APPOINTMENT_COLLECTION_ID=
    NEXT_PUBLIC_BUCKET_ID=
    NEXT_PUBLIC_ADMIN_PASSKEY=111111
    ```

4. **Run the app**

    ```bash
    npm run dev
    ```

    Visit [http://localhost:3000](http://localhost:3000)

---

## Project Structure

```
healthcare/
├── app/
│   ├── admin/
│   ├── patients/
│   └── api/
├── components/
├── constants/
├── lib/
├── public/
└── types/
```

---

##