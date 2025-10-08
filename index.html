<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Uni-Central | Demo</title>
    <script src="https://cdn.tailwindcss.com/3.4.1"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;900&display=swap" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
    <script src="https://unpkg.com/react@18/umd/react.development.js"></script>
    <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
    <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
    <script type="module">
        // This is a placeholder for the Gemini AI library.
        // In a real environment, you would use the actual library.
        window.GoogleGenerativeAI = class {
            constructor(apiKey) {
                console.log("GoogleGenerativeAI initialized with key:", apiKey ? "provided" : "not provided");
            }
            getGenerativeModel() {
                return {
                    generateContent: async (request) => {
                         console.log("Gemini API call mocked.", request);
                         await new Promise(resolve => setTimeout(resolve, 1500)); // Simulate network delay
                         const userQuery = request.contents[request.contents.length - 1].parts[0].text.toLowerCase();
                         let botText = "Lo siento, estoy teniendo problemas para conectarme. Intenta más tarde.";

                         if (userQuery.includes("hola") || userQuery.includes("quién sos")) {
                             botText = "¡Buenas! Soy **Uni-Bot** 🤖. Estoy para darte una mano con **Uni-Central**, mientras no me interrumpas la ronda de mates. 😉";
                         } else if (userQuery.includes("cursos")) {
                             botText = "¡**Fácil**! Apenas entrás al portal, vas a ver una sección con tu **progreso** y tus **cursos pendientes**. Está todo a la vista. 👍";
                         } else if (userQuery.includes("creó") || userQuery.includes("creador")) {
                            botText = "Me creó **Jorge Luis Álamo** (el Administrador). Él pensó en todo **Uni-Central**. ¡Un genio! 😉";
                         } else if (userQuery.includes("pdf")) {
                             botText = "¡Qué buena iniciativa! Por ahora, la descarga de **PDF** es un lujo para **Supervisores**, **Socios** y **Admins**. Quién te dice, quizás en el futuro... 😉";
                         }

                         return {
                             response: {
                                 text: () => botText
                             }
                         };
                    }
                };
            }
        };
    </script>
    <style>
      body {
        font-family: 'Inter', sans-serif;
      }
      @keyframes rotate { 
        from { transform: rotate(0deg); } 
        to { transform: rotate(360deg); } 
      }
      .animate-rotate {
        animation: rotate 20s infinite linear;
      }
      .animate-rotate-reverse {
        animation: rotate 20s infinite linear reverse;
      }
      @keyframes fadeIn {
        from { opacity: 0; transform: translateY(20px); }
        to { opacity: 1; transform: translateY(0); }
      }
      .animate-fade-in {
        animation: fadeIn 0.5s ease-out forwards;
      }
      details > summary {
        list-style: none;
      }
      details > summary::-webkit-details-marker {
        display: none;
      }
      details[open] .details-arrow, details.group-open .details-arrow {
        transform: rotate(180deg);
      }
      details[open] summary ~ *, details.group-open summary ~ * {
        animation: fadeIn 0.3s ease-in-out;
      }
      @keyframes pulse-slow {
        0%, 100% { transform: scale(1); opacity: 0.9; }
        50% { transform: scale(1.02); opacity: 1; }
      }
      .animate-pulse-slow {
        animation: pulse-slow 4s infinite ease-in-out;
      }
      @keyframes wiggle {
        0%, 100% { transform: rotate(-3deg); }
        50% { transform: rotate(3deg); }
      }
      .animate-wiggle {
        animation: wiggle 1.5s ease-in-out infinite;
      }
      @keyframes shake-gentle {
        0%, 100% { transform: translateX(0) rotate(0); }
        25% { transform: translateX(-2px) rotate(-1deg); }
        75% { transform: translateX(2px) rotate(1deg); }
      }
      .animate-shake-gentle {
        animation: shake-gentle 2s infinite ease-in-out;
      }
      /* Tooltip styles */
      .tooltip {
        visibility: hidden;
        opacity: 0;
        transition: opacity 0.2s;
      }
      .has-tooltip:hover .tooltip {
        visibility: visible;
        opacity: 1;
      }
      /* Chat bubble styles */
      .chat-bubble-user {
        background-color: #00a9e0;
        color: white;
        border-radius: 1.25rem 1.25rem 0.25rem 1.25rem;
      }
      .chat-bubble-bot {
        background-color: #f3f4f6;
        color: #1f2937;
        border-radius: 1.25rem 1.25rem 1.25rem 0.25rem;
      }
      .dark .chat-bubble-bot {
        background-color: #374151;
        color: #f3f4f6;
      }
      @keyframes typing-dots {
        0%, 20% { content: '.'; }
        40%, 60% { content: '..'; }
        80%, 100% { content: '...'; }
      }
      .typing-indicator::after {
        content: '.';
        animation: typing-dots 1.5s infinite;
        display: inline-block;
        width: 1.5em;
        text-align: left;
      }
      /* Uni-Bot animation */
      .uni-bot-mouth {
        transition: d 0.3s ease-in-out;
      }
      .uni-bot-button:hover .uni-bot-mouth {
        d: path("M 8 15 Q 12 18 16 15");
      }
      
      /* MODIFICATION: New login title animation */
      @keyframes shimmer {
        0% { background-position: -500px 0; }
        100% { background-position: 500px 0; }
      }
      .title-shimmer {
        background: linear-gradient(to right, #0d2235 20%, #00a9e0 50%, #0d2235 80%);
        background-size: 200% auto;
        color: transparent;
        background-clip: text;
        -webkit-background-clip: text;
        animation: shimmer 5s infinite linear;
      }

      /* Letter animation for header title */
      @keyframes lift {
        0%, 100% { transform: translateY(0); }
        50% { transform: translateY(-5px); }
      }
      .animated-letter-lift {
        display: inline-block;
        animation: lift 2.5s ease-in-out infinite;
      }
      /* Calendar animation */
      @keyframes calendar-fade {
        from { opacity: 0; transform: scale(0.98); }
        to { opacity: 1; transform: scale(1); }
      }
      .calendar-grid-animating {
        animation: calendar-fade 0.3s ease-in-out;
      }
      @keyframes legend-pulse {
        0%, 100% { box-shadow: 0 0 0 0 rgba(0, 169, 224, 0.4); }
        50% { box-shadow: 0 0 0 5px rgba(0, 169, 224, 0); }
      }
      .legend-pulse {
        animation: legend-pulse 2s infinite;
      }
      /* Star pulse animation */
      @keyframes star-pulse {
        0%, 100% { transform: scale(1); }
        50% { transform: scale(1.2); }
      }
      .animate-star-pulse {
        animation: star-pulse 2s infinite;
      }
    </style>
</head>
<body class="bg-gray-50 text-gray-800 dark:bg-[#0d2235] dark:text-gray-200">
    <div id="root"></div>
    <script type="text/babel">
// This React application is a comprehensive dashboard for "Uni-Central",
// a fictional training platform for a Chevrolet dealership.
// It features role-based access control, detailed progress tracking,
// internal communications, a help system, and an AI-powered chatbot.
// The code is structured with modern React hooks, context for state management,
// and functional components for a clean and maintainable architecture.

const { useState, useEffect, useCallback, useRef, createContext, useContext, forwardRef } = React;

// --- Global CDN Libraries ---
// These are assigned to window objects by their respective script tags.
// We declare them here for clarity.
var html2canvas;
var jspdf;
var GoogleGenerativeAI; 

// --- GEMINI AI SETUP ---
// IMPORTANT: The API_KEY is a placeholder and will not work.
// The GoogleGenerativeAI class is also mocked in the head for demonstration purposes.
const API_KEY = "YOUR_API_KEY_HERE"; 
let ai;
if (window.GoogleGenerativeAI) {
  try {
    const genAI = new window.GoogleGenerativeAI(API_KEY);
    ai = genAI.getGenerativeModel({ model: "gemini-1.5-flash" });
  } catch (e) {
    console.error("Error initializing GoogleGenAI. Uni-Bot might be disabled.", e);
  }
} else {
    console.warn("GoogleGenerativeAI not available. Uni-Bot will be disabled.");
}

// This URL points to a Google Apps Script that acts as a simple backend.
// It's used to fetch data from and post data to a Google Sheet.
const SCRIPT_URL = "https://script.google.com/macros/s/AKfycbx0QrOQjlE051RR-yHZVi2dhCBDS5D-0P975bMyHK-WfTh9_z95AfYRThV9Gz1FVP-g/exec";

// --- DATA FETCHING ---
// Fetches data from the deployed Google Apps Script.
// If the fetch fails, it falls back to using local mock data.
const fetchDatabaseData = async () => {
  try {
    const response = await fetch(SCRIPT_URL);
    if (!response.ok) {
      throw new Error(`Network response was not ok: ${response.statusText}`);
    }
    const data = await response.json();
    return data;
  } catch (error) {
    console.error("Failed to fetch data from Google Sheet:", error);
    // Using a custom modal/alert would be better, but alert is used for simplicity here.
    // In a production app, you'd have a more robust error handling UI.
    alert("No se pudo conectar con la base de datos. Se cargarán datos de demostración.");
    return MOCK_DB;
  }
};

// --- DATA WRITING ---
// Posts data to the Google Apps Script.
// Uses 'no-cors' mode, which is a common requirement for simple Apps Script web app interactions.
// This means we send the data but don't get a readable response back.
const postDataToSheet = async (action, payload) => {
    try {
        const response = await fetch(SCRIPT_URL, {
            method: 'POST',
            mode: 'no-cors', // Important for Apps Script web apps
            headers: {
                'Content-Type': 'application/json',
            },
            body: JSON.stringify({ action, payload }),
        });
        // no-cors mode means we can't read the response, but the request is sent.
        console.log(`Action '${action}' sent to the server.`);
    } catch (error) {
        console.error(`Error posting data for action '${action}':`, error);
    }
};

// --- MOCK API SERVICE (Fallback) ---
// MODIFICATION: Added birthdate field to users and surveyData for CX features.
const MOCK_DB = {
  config: {
    login_description: "Portal informativo de Universidad Chevrolet.\nCentral Autos S.A. - Agente Oficial Chevrolet",
    footer_credits: "Sitio web creado por Jorge Luis Álamo para Central Autos S.A..\n@Chevrolet.CentralAutos | 2025 | Todos los derechos reservados.",
    last_data_update: "2025-08-12"
  },
  users: [
      { "id": "35938036", "name": "Jorge Luis Alamo", "role": "ADMINISTRADOR", "teamId": null, "gender": "m", "birthdate": "1994-08-25" },
      { "id": "39460775", "name": "Adrián Nenna", "role": "ALUMNO", "teamId": "Peralta", "gender": "m", "birthdate": "1997-09-02" },
      { "id": "39000803", "name": "Enzo Bartschat", "role": "SUPERVISOR", "teamId": "Mesa", "gender": "m", "birthdate": "1997-03-15" },
      { "id": "44609289", "name": "Ignacio rotela", "role": "ALUMNO", "teamId": "Peralta", "gender": "m", "birthdate": "2003-01-20" },
      { "id": "9999", "name": "Jorge Luis Alamo", "role": "ADMINISTRADOR", "teamId": null, "gender": "m", "birthdate": "1994-08-25" },
      { "id": "37243357", "name": "Jaqueline Quiroga", "role": "ALUMNO", "teamId": "Gerencia", "gender": "f", "birthdate": "1995-11-05" },
      { "id": "40081593", "name": "Juan Gisondi", "role": "SUPERVISOR", "teamId": "Gisondi", "gender": "m", "birthdate": "1998-02-18" },
      { "id": "38891288", "name": "Mariano Medina", "role": "ALUMNO", "teamId": "Gisondi", "gender": "m", "birthdate": "1997-01-30" },
      { "id": "39906856", "name": "Matías Maldonado", "role": "ALUMNO", "teamId": "Ibarra", "gender": "m", "birthdate": "1998-04-22" },
      { "id": "36093382", "name": "Micaela Luty", "role": "ALUMNO", "teamId": "Luty", "gender": "f", "birthdate": "1994-06-11" },
      { "id": "36948339", "name": "Mauro Luty", "role": "SUPERVISOR", "teamId": "Luty", "gender": "m", "birthdate": "1995-05-19" },
      { "id": "41151632", "name": "Nazarena Ibarra", "role": "SUPERVISOR", "teamId": "Ibarra", "gender": "f", "birthdate": "1999-07-08" },
      { "id": "39209188", "name": "Sol Peña", "role": "ALUMNO", "teamId": "Ibarra", "gender": "f", "birthdate": "1997-08-11" },
      { "id": "37990623", "name": "Yanet Peralta", "role": "SUPERVISOR", "teamId": "Peralta", "gender": "f", "birthdate": "1996-08-15" },
      { "id": "38892448", "name": "Ivana Grossi", "role": "ALUMNO", "teamId": "Administracion", "gender": "f", "birthdate": "1997-02-01" },
      { "id": "35339317", "name": "Mayra Gisondi", "role": "ALUMNO", "teamId": "Administracion", "gender": "f", "birthdate": "1993-10-10" },
      { "id": "33708298", "name": "Nora Yañez", "role": "ALUMNO", "teamId": "Administracion", "gender": "f", "birthdate": "1988-12-25" },
      { "id": "40060507", "name": "Evelin Diaz", "role": "ALUMNO", "teamId": "Administracion", "gender": "f", "birthdate": "1998-06-30" },
      { "id": "39065149", "name": "Macarena Chiodo", "role": "ALUMNO", "teamId": "Administracion", "gender": "f", "birthdate": "1997-04-04" },
      { "id": "33297161", "name": "Nahuel Gisondi", "role": "SOCIO", "teamId": null, "gender": "m", "birthdate": "1988-01-01" },
      { "id": "20736902", "name": "Fabio Caniglia", "role": "SOCIO", "teamId": null, "gender": "m", "birthdate": "1970-01-01" },
      { "id": "34480681", "name": "Alejandro Guiliano", "role": "SOCIO", "teamId": null, "gender": "m", "birthdate": "1990-01-01" },
      { "id": "34587571", "name": "Damián Quiroga", "role": "SOCIO", "teamId": null, "gender": "m", "birthdate": "1991-01-01" },
      { "id": "2323", "name": "Gerencia", "role": "SUPERVISOR", "teamId": "Gerencia", "gender": "m", "birthdate": "1980-01-01" },
      { "id": "2424", "name": "Mesa", "role": "ALUMNO", "teamId": "Mesa", "gender": "m", "birthdate": "1980-01-01" },
      { "id": "2525", "name": "Administración", "role": "SUPERVISOR", "teamId": "Administracion", "gender": "m", "birthdate": "1980-01-01" },
      { "id": "3333", "name": "Central Autos", "role": "SOCIO", "teamId": null, "gender": "m", "birthdate": "1980-01-01" },
      { "id": "8989", "name": "Test 3", "role": "SUPERVISOR", "teamId": "Mesa", "gender": "m", "birthdate": "1980-01-01" }
  ],
  teams: [
      { "id": "Peralta", "name": "Equipo Yanet", "supervisorId": "37990623" },
      { "id": "Gisondi", "name": "Equipo Juan", "supervisorId": "40081593" },
      { "id": "Ibarra", "name": "Equipo Nazarena", "supervisorId": "41151632" },
      { "id": "Luty", "name": "Equipo Mauro", "supervisorId": "36948339" },
      { "id": "Gerencia", "name": "Equipo Gerencia", "supervisorId": "2323" },
      { "id": "Mesa", "name": "Equipo Mesa de planes", "supervisorId": "39000803" },
      { "id": "Administracion", "name": "Equipo Administración", "supervisorId": "2525" }
  ],
  courses: {
      "35938036": { "userId": "35938036", "total": 0, "completed": 0, "deadline": "2025-08-31", "pendingCourses": [] },
      "39460775": { "userId": "39460775", "total": 3, "completed": 3, "deadline": "2025-08-31", "pendingCourses": ["WBT Administrativo - Cesiones de derechos", "WBT Administrativo - Validación de personas", "WBT Administrativo - WBT – Prendas"] },
      "39000803": { "userId": "39000803", "total": 6, "completed": 6, "deadline": "2025-08-31", "pendingCourses": [] },
      "44609289": { "userId": "44609289", "total": 3, "completed": 3, "deadline": "2025-08-31", "pendingCourses": [] },
      "9999": { "userId": "9999", "total": 0, "completed": 0, "deadline": "2025-08-31", "pendingCourses": [] },
      "37243357": { "userId": "37243357", "total": 6, "completed": 6, "deadline": "2025-08-31", "pendingCourses": [] },
      "40081593": { "userId": "40081593", "total": 4, "completed": 2, "deadline": "2025-08-31", "pendingCourses": [] },
      "38891288": { "userId": "38891288", "total": 6, "completed": 6, "deadline": "2025-08-31", "pendingCourses": [] },
      "39906856": { "userId": "39906856", "total": 3, "completed": 3, "deadline": "2025-08-31", "pendingCourses": [] },
      "36093382": { "userId": "36093382", "total": 3, "completed": 3, "deadline": "2025-08-31", "pendingCourses": [] },
      "36948339": { "userId": "36948339", "total": 6, "completed": 6, "deadline": "2025-08-31", "pendingCourses": [] },
      "41151632": { "userId": "41151632", "total": 4, "completed": 3, "deadline": "2025-08-31", "pendingCourses": [] },
      "39209188": { "userId": "39209188", "total": 4, "completed": 4, "deadline": "2025-08-31", "pendingCourses": [] },
      "37990623": { "userId": "37990623", "total": 3, "completed": 3, "deadline": "2025-08-31", "pendingCourses": [] },
      "38892448": { "userId": "38892448", "total": 0, "completed": 0, "deadline": "2025-08-31", "pendingCourses": [] },
      "35339317": { "userId": "35339317", "total": 14, "completed": 9, "deadline": "2025-08-31", "pendingCourses": [] },
      "33708298": { "userId": "33708298", "total": 14, "completed": 7, "deadline": "2025-08-31", "pendingCourses": [] },
      "40060507": { "userId": "40060507", "total": 14, "completed": 10, "deadline": "2025-08-31", "pendingCourses": [] },
      "39065149": { "userId": "39065149", "total": 0, "completed": 0, "deadline": "2025-08-31", "pendingCourses": [] },
      "33297161": { "userId": "33297161", "total": 0, "completed": 0, "deadline": "2025-08-31", "pendingCourses": [] },
      "20736902": { "userId": "20736902", "total": 0, "completed": 0, "deadline": "2025-08-31", "pendingCourses": [] },
      "34480681": { "userId": "34480681", "total": 0, "completed": 0, "deadline": "2025-08-31", "pendingCourses": [] },
      "34587571": { "userId": "34587571", "total": 0, "completed": 0, "deadline": "2025-08-31", "pendingCourses": [] }
  },
  vctCourses: {
      "37243357": [{ "userId": "37243357", "name": "IPT VENTAS - SPARK EV [VD-00002-AR-IPT]", "date": "2025-08-06", "startTime": "05:00", "endTime": "14:00", "location": "Arawak", "type": "Presencial", "status": "Evaluación pendiente" }],
      "39065149": [{ "userId": "39065149", "name": "VCT Administrativo - Gestión de talentos; Planes de sucesión. [ADM-00015-AR-VCT]", "date": "2025-07-28", "startTime": "05:00", "endTime": "14:00", "location": "online", "type": "online", "status": "Aprobado" }],
      "35938036": [{ "userId": "35938036", "name": "VCT Liderazgo - PDLC - Liderazgo del futuro", "date": "2025-07-16", "startTime": "09:00", "endTime": "12:00", "location": "online", "type": "online", "status": "Aprobado" }],
      "36948339": [{ "userId": "36948339", "name": "VCT Liderazgo - PDLC - Liderazgo del futuro", "date": "2025-07-16", "startTime": "09:00", "endTime": "12:00", "location": "online", "type": "online", "status": "Aprobado" }],
      "37990623": [{ "userId": "37990623", "name": "VCT Liderazgo - PDLC - Liderazgo del futuro", "date": "2025-07-16", "startTime": "09:00", "endTime": "12:00", "location": "online", "type": "online", "status": "Aprobado" }]
  },
  news: [
      { "id": "news1", "date": "2025-08-08", "title": "Uni-Central: NUEVO PORTAL PARA CENTRAL AUTOS", "content": "Ya se encuentra disponible el nuevo Portal Uni-Central", "targetRoles": ["ALUMNO", "SUPERVISOR", "SOCIO", "ADMINISTRADOR"], "reactions": { "likes": [], "dislikes": [] } }
  ],
  franchiseMeeting: {
      "compliancePercentage": 87, "points": 5, "salesWbt": 100, "salesVct": 100, "leadershipWbt": 100, "leadershipVct": 50, "permanentEligibility": "ELEGIBLE", "monthlyEligibility": "ELEGIBLE", "q1_progress": 100, "q2_progress": 100, "q3_progress": 87, "q4_progress": 0
  },
  faq: [
      { "question": "¿Cada cuánto se actualiza la información?", "answer": "La información es actualizada de forma diaria. El portal se encuentra en constante evolución, y puede presentar algunos problemas." }
  ],
  motivationalPhrases: [ 
      { "timeOfDay": "morning", "phrase": "El éxito es la suma de pequeños esfuerzos." },
      { "timeOfDay": "afternoon", "phrase": "La única forma de hacer un gran trabajo es amar lo que haces." },
      { "timeOfDay": "night", "phrase": "Cree que puedes y ya estás a medio camino." }
  ],
  internalCourses: [
      { "title": "Optimiza tu Día con Google Calendar", "description": "Aprende a gestionar tu agenda...", "buttonText": "Ingresar al link", "videoUrl": "https://www.youtube.com/watch?v=..." }
  ],
  interestLinks: [
      { "name": "Chevrolet", "url": "https://www.chevrolet.com.ar/" },
      { "name": "Central Autos", "url": "https://www.chevroletcentralautos.com.ar/" },
      { "name": "Chucu", "url": "https://www.chevroletcentralautos.com.ar/" },
      { "name": "Infobae", "url": "https://www.infobae.com/" }
  ],
  holidays: [
      { "date": "2025-01-01", "name": "Año Nuevo", "type": "feriado" },
      { "date": "2025-03-03", "name": "Carnaval", "type": "feriado" },
      { "date": "2025-08-10", "name": "Cierre de Objetivos Q3", "type": "recordatorio" }
  ],
  ephemerides: [],
  surveyData: [
      { "userId": "39460775", "timestamp": "2025-08-10T10:00:00Z", "satisfaction": 5, "recommend": 5, "botHelpful": true, "feedback": "¡El portal es genial! Muy fácil de usar." },
      { "userId": "44609289", "timestamp": "2025-08-10T11:30:00Z", "satisfaction": 4, "recommend": 5, "botHelpful": true, "feedback": "Me gustaría que la sección de noticias se actualice más seguido." },
      { "userId": "37243357", "timestamp": "2025-08-11T14:00:00Z", "satisfaction": 3, "recommend": 3, "botHelpful": false, "feedback": "El bot no entendió mi pregunta sobre los cursos VCT." },
      { "userId": "38891288", "timestamp": "2025-08-11T18:45:00Z", "satisfaction": 5, "recommend": 4, "botHelpful": true, "feedback": "" },
      { "userId": "39906856", "timestamp": "2025-08-12T09:15:00Z", "satisfaction": 4, "recommend": 4, "botHelpful": null, "feedback": "No usé el bot, pero el resto funciona bien." }
  ]
};

// --- UTILS ---
// A collection of helper functions used throughout the application.

const getFirstName = (fullName) => {
  if (!fullName) return '';
  return fullName.split(' ')[0];
};

const getRoleDisplayName = (user) => {
  if (!user) return '';
  const { role, gender } = user;
  if (role === 'ALUMNO') return gender === 'f' ? 'Alumna' : 'Alumno';
  if (role === 'SUPERVISOR') return gender === 'f' ? 'Supervisora' : 'Supervisor';
  return role.charAt(0).toUpperCase() + role.slice(1).toLowerCase();
};

const getWelcomeGreeting = (user) => {
    if (!user) return '¡Bienvenido/a';
    return user.gender === 'f' ? '¡Bienvenida' : '¡Bienvenido';
};

const getDailyPhrase = (phrases) => {
    if (!phrases || phrases.length === 0) return "¡Que tengas un excelente día!";
    const hour = new Date().getHours();
    let timeOfDay;
    if (hour >= 5 && hour < 12) timeOfDay = 'morning';
    else if (hour >= 12 && hour < 20) timeOfDay = 'afternoon';
    else timeOfDay = 'night';
    const applicablePhrases = phrases.filter(p => p.timeOfDay === timeOfDay);
    if (applicablePhrases.length === 0) {
        return phrases[Math.floor(Math.random() * phrases.length)]?.phrase || "¡Bienvenido/a!";
    }
    return applicablePhrases[Math.floor(Math.random() * applicablePhrases.length)].phrase;
};

const calculateDaysLeft = (deadline) => {
    if (!deadline) return 0;
    const today = new Date();
    const endDate = new Date(deadline + 'T23:59:59');
    const diffTime = endDate.getTime() - today.getTime();
    if (diffTime < 0) return 0;
    return Math.ceil(diffTime / (1000 * 60 * 60 * 24));
};

const logAccessLocal = (userId) => {
    try {
        const logKey = `accessLog_${userId}`;
        let log = JSON.parse(localStorage.getItem(logKey) || '[]');
        log.unshift(new Date().toISOString());
        log = log.slice(0, 10); // Keep only the last 10 accesses
        localStorage.setItem(logKey, JSON.stringify(log));
        postDataToSheet('logAccess', { userId });
    } catch (e) {
        console.error("Failed to log access", e);
    }
};

const getAccessLogLocal = (userId) => {
    try {
        const logKey = `accessLog_${userId}`;
        return JSON.parse(localStorage.getItem(logKey) || '[]');
    } catch (e) {
        return [];
    }
};


const getReadNotifications = () => {
    try {
        return JSON.parse(localStorage.getItem('uniCentral_read_notifications') || '{}');
    } catch (e) {
        return {};
    }
};

const markNotificationsAsRead = (notificationIds) => {
    if (!notificationIds || notificationIds.length === 0) return;
    try {
        const readNotifs = getReadNotifications();
        const now = new Date().toISOString();
        notificationIds.forEach(id => {
            if (id) readNotifs[id] = now;
        });
        localStorage.setItem('uniCentral_read_notifications', JSON.stringify(readNotifs));
    } catch (e) {
        console.error("Failed to mark notifications as read", e);
    }
};

const generateNotifications = (db, currentUser) => {
  const notifications = [];
  const userCourses = db.courses[currentUser.id];
  const readNotifs = getReadNotifications();
  const threeDaysAgo = new Date();
  threeDaysAgo.setDate(threeDaysAgo.getDate() - 3);

  const checkAndPush = (id, title) => {
      // Don't show notifications that were read more than 3 days ago
      const readAt = readNotifs[id];
      if (readAt && new Date(readAt) < threeDaysAgo) return;
      notifications.push({ id, title, unread: !readAt });
  };

  if (db.news && db.news.filter(n => n.targetRoles.includes(currentUser.role)).length > 0) checkAndPush('news', 'Se agregaron nuevas novedades');
  if (db.internalCourses && db.internalCourses.length > 0) checkAndPush('training', 'Hay nuevas capacitaciones internas');
  if (userCourses && userCourses.pendingCourses.length > 0) checkAndPush('courses', `Tenes ${userCourses.pendingCourses.length} cursos pendientes`);
  const daysLeft = calculateDaysLeft(userCourses?.deadline);
  if (userCourses && userCourses.pendingCourses.length > 0 && daysLeft <= 5 && daysLeft > 0) checkAndPush('deadline', `¡La fecha límite es en ${daysLeft} días!`);
 
  return notifications;
};

const generatePDF = async (pdfReportRef, currentUser, setIsLoading) => {
    if (!pdfReportRef.current || !window.html2canvas || !window.jspdf) {
        alert('Error: Librería de PDF no cargada.');
        return;
    }
    setIsLoading(true);
    const originalVisibility = pdfReportRef.current.style.visibility;
    pdfReportRef.current.style.visibility = 'visible'; 

    try {
        const canvas = await window.html2canvas(pdfReportRef.current, { scale: 2, useCORS: true });
        const imgData = canvas.toDataURL('image/png');
        const pdf = new window.jspdf.jsPDF({ orientation: 'p', unit: 'mm', format: 'a4' });
        const pdfWidth = pdf.internal.pageSize.getWidth();
        const pdfHeight = pdf.internal.pageSize.getHeight();
        const imgProps = pdf.getImageProperties(imgData);
        const imgHeight = (imgProps.height * pdfWidth) / imgProps.width;
        
        let heightLeft = imgHeight;
        let position = 0;

        pdf.addImage(imgData, 'PNG', 0, position, pdfWidth, imgHeight);
        heightLeft -= pdfHeight;

        while (heightLeft > 0) {
            position = heightLeft - imgHeight;
            pdf.addPage();
            pdf.addImage(imgData, 'PNG', 0, position, pdfWidth, imgHeight);
            heightLeft -= pdfHeight;
        }
        
        pdf.save(`Reporte_Uni-Central_${currentUser.name}_${new Date().toLocaleDateString('es-CA')}.pdf`);
    } catch (error) {
        console.error("Error generating PDF:", error);
        alert("Hubo un error al generar el PDF.");
    } finally {
        pdfReportRef.current.style.visibility = originalVisibility; 
        setIsLoading(false);
    }
};

const exportToExcel = async (db, currentUser) => {
  // This is a placeholder. A real implementation would use a library like 'xlsx'
  // or call a server endpoint that generates the Excel file.
  console.log("Exporting to Excel...", { db, currentUser });
  alert("La funcionalidad de exportar a Excel aún no está implementada en este entorno de demostración.");
};

// --- SHARED COMPONENTS ---
// Reusable UI elements used across different parts of the application.

const Card = ({ children, className = '' }) => (
  <div className={`bg-white dark:bg-[#1f2937] rounded-2xl border border-gray-200 dark:border-[#374151] shadow-lg text-gray-700 dark:text-gray-300 ${className}`}>
    {children}
  </div>
);

const Loader = () => (
  <div className="fixed top-0 left-0 w-full h-full bg-black/60 backdrop-blur-sm flex justify-center items-center z-[1000]">
    <div className="w-10 h-10 border-4 border-gray-200 border-t-[#00a9e0] rounded-full animate-spin"></div>
  </div>
);

const Modal = ({ isOpen, onClose, title, children, canBeClosed = true }) => {
    if (!isOpen) return null;
    return (
        <div className="fixed inset-0 bg-black/60 backdrop-blur-sm flex justify-center items-center z-[1000] animate-fade-in" onClick={canBeClosed ? onClose : undefined}>
            <div className="w-11/12 max-w-2xl max-h-[90vh] flex flex-col bg-white dark:bg-[#1f2937] rounded-2xl shadow-2xl border border-gray-200 dark:border-[#374151]" onClick={(e) => e.stopPropagation()}>
                <div className="p-4 sm:p-6 border-b border-gray-200 dark:border-[#374151] flex justify-between items-center flex-shrink-0">
                    <h2 className="text-xl sm:text-2xl font-bold text-[#0d2235] dark:text-white text-center w-full">{title}</h2>
                    {canBeClosed && <button onClick={onClose} className="text-gray-400 hover:text-gray-800 dark:hover:text-white text-3xl">&times;</button>}
                </div>
                <div className="flex-1 overflow-y-auto min-h-0">{children}</div>
            </div>
        </div>
    );
};

// --- SVG Progress Circle Component ---
// This is a self-contained, dependency-free component to render a circular progress bar.
// It replaces the previous Recharts-based component to improve reliability and performance.
const SvgProgressCircle = ({ progress }) => {
    const [displayProgress, setDisplayProgress] = useState(0);

    useEffect(() => {
        // Animate the progress from 0 to the target value
        const timeout = setTimeout(() => setDisplayProgress(progress), 100);
        return () => clearTimeout(timeout);
    }, [progress]);

    const size = 250;
    const strokeWidth = 20;
    const center = size / 2;
    const radius = center - strokeWidth / 2;
    const circumference = 2 * Math.PI * radius;

    const offset = circumference - (displayProgress / 100) * circumference;

    const progressColor = progress >= 100 ? 'text-[#00a9e0]' : progress >= 80 ? 'text-yellow-500' : 'text-red-500';
    const fontSizeClass = progress === 100 ? 'text-5xl sm:text-6xl' : 'text-6xl sm:text-7xl';

    return (
        <div className="relative animate-pulse-slow" style={{ width: size, height: size }}>
            <svg width={size} height={size} viewBox={`0 0 ${size} ${size}`} className="-rotate-90">
                <defs>
                    <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
                        <feDropShadow dx="3" dy="5" stdDeviation="5" floodColor="#000000" floodOpacity="0.2"/>
                    </filter>
                </defs>
                {/* Background Circle */}
                <circle
                    className="text-gray-200 dark:text-gray-700"
                    stroke="currentColor"
                    strokeWidth={strokeWidth}
                    fill="transparent"
                    r={radius}
                    cx={center}
                    cy={center}
                />
                {/* Foreground Circle (Progress) */}
                <circle
                    className={`${progressColor}`}
                    style={{ transition: 'stroke-dashoffset 1.5s ease-out' }}
                    stroke="currentColor"
                    strokeWidth={strokeWidth}
                    strokeDasharray={circumference}
                    strokeDashoffset={offset}
                    strokeLinecap="round"
                    fill="transparent"
                    r={radius}
                    cx={center}
                    cy={center}
                    filter="url(#shadow)"
                />
            </svg>
            <div className="absolute inset-0 flex items-center justify-center">
                <span className={`${fontSizeClass} font-bold text-[#0d2235] dark:text-white [text-shadow:2px_2px_4px_rgba(0,0,0,0.1)] dark:[text-shadow:2px_2px_6px_rgba(0,0,0,0.4)]`}>
                    {`${progress}%`}
                </span>
            </div>
        </div>
    );
};


// --- AUTH CONTEXT & PROVIDER ---
// Manages the global authentication state (current user, impersonation status)
// and provides it to all components wrapped within it.
const AuthContext = createContext(undefined);

const AuthProvider = ({ children }) => {
    const [currentUser, setCurrentUser] = useState(null);
    const [originalUser, setOriginalUser] = useState(null); // For admin impersonation
    const [db, setDb] = useState(null);

    const login = useCallback((user, database) => {
        setCurrentUser(user);
        setDb(database);
        logAccessLocal(user.id);
    }, []);

    const logout = useCallback(() => {
        setCurrentUser(null);
        setOriginalUser(null);
        setDb(null);
    }, []);

    const impersonate = useCallback((userId) => {
        if (!db) return;
        const userToImpersonate = db.users.find(u => String(u.id) === String(userId));
        if (userToImpersonate && currentUser?.role === 'ADMINISTRADOR') {
            if (!originalUser) setOriginalUser(currentUser); // Save the original admin user
            setCurrentUser(userToImpersonate);
        }
    }, [db, currentUser, originalUser]);

    const returnToAdmin = useCallback(() => {
        if (originalUser) {
            setCurrentUser(originalUser);
            setOriginalUser(null);
        }
    }, [originalUser]);

    const value = { currentUser, setCurrentUser, originalUser, login, logout, impersonate, returnToAdmin, db, setDb };
    return <AuthContext.Provider value={value}>{children}</AuthContext.Provider>;
};

const useAuth = () => {
    const context = useContext(AuthContext);
    if (context === undefined) throw new Error('useAuth must be used within an AuthProvider');
    return context;
};

// --- DASHBOARD SECTION COMPONENTS ---
// Components that represent distinct sections within the main dashboard.

const VctStatusBadge = ({ status }) => {
    const config = {
        'Aprobado': 'bg-green-100 text-green-800 dark:bg-green-900/50 dark:text-green-300',
        'Próximamente': 'bg-blue-100 text-blue-800 dark:bg-blue-900/50 dark:text-blue-300',
        'Pendiente de evaluación': 'bg-yellow-100 text-yellow-800 dark:bg-yellow-900/50 dark:text-yellow-300',
        'Reprobado': 'bg-red-100 text-red-800 dark:bg-red-900/50 dark:text-red-300',
        'No asistió': 'bg-red-100 text-red-800 dark:bg-red-900/50 dark:text-red-300'
    };
    return <div className={`text-sm font-semibold px-3 py-1 rounded-full text-center ${config[status] || 'bg-gray-100 text-gray-800'}`}>{status}</div>;
};

const VctSection = ({ courses }) => {
    if (!courses || courses.length === 0) return null;
    return (
        <section className="mt-10 animate-fade-in">
            <h2 className="text-2xl font-bold mb-4 border-l-4 border-green-500 pl-4 text-[#0d2235] dark:text-white">Cursos VCT / PRESENCIALES</h2>
            <Card className="p-6 space-y-4">
                {courses.map((course, i) => (
                    <div key={i} className="bg-gray-50 dark:bg-gray-800 p-4 rounded-lg flex flex-col sm:flex-row justify-between sm:items-center gap-4">
                        <div className="flex-grow">
                            <p className="font-bold text-lg">{course.name}</p>
                            <p className="text-sm text-gray-500 font-semibold">{course.type}</p>
                        </div>
                        <div className="text-sm text-gray-600 dark:text-gray-300 text-left sm:text-right">
                            <p><span className="font-semibold">Fecha:</span> {course.date}</p>
                            <p><span className="font-semibold">Horario:</span> {course.startTime} - {course.endTime}</p>
                        </div>
                        <div className="flex-shrink-0"><VctStatusBadge status={course.status} /></div>
                    </div>
                ))}
            </Card>
        </section>
    );
};

const TeamVctSection = ({ db, users, title }) => {
    const allVctCourses = users.flatMap(user => (db.vctCourses[user.id] || []).map(course => ({ ...course, user })));
    if (allVctCourses.length === 0) return null;
    const approvedCount = allVctCourses.filter(c => c.status === 'Aprobado').length;
    const approvalPercentage = allVctCourses.length > 0 ? Math.round((approvedCount / allVctCourses.length) * 100) : 0;
    const approvalColor = approvalPercentage < 50 ? 'text-red-500' : (approvalPercentage < 80 ? 'text-yellow-500' : 'text-green-500');
    return (
        <section className="mt-10 animate-fade-in">
            <h2 className="text-2xl font-bold mb-4 border-l-4 border-teal-500 pl-4 text-[#0d2235] dark:text-white">{title}</h2>
            <Card className="p-6 grid grid-cols-1 lg:grid-cols-3 gap-6">
                <div className="lg:col-span-2">
                    <h3 className="text-xl font-bold mb-4">Listado de Cursos</h3>
                    <div className="space-y-4 max-h-[400px] overflow-y-auto pr-2">
                        {allVctCourses.map((course, i) => (
                            <div key={`${course.user.id}-${i}`} className="bg-gray-50 dark:bg-gray-800 p-4 rounded-lg flex justify-between items-center gap-4">
                                <div>
                                    <p className="font-bold text-md">{course.name}</p>
                                    <p className="text-sm font-semibold text-gray-600 dark:text-gray-400">{course.user.name}</p>
                                </div>
                                <VctStatusBadge status={course.status} />
                            </div>
                        ))}
                    </div>
                </div>
                <div className="lg:col-span-1 text-center flex flex-col justify-center border-t lg:border-t-0 lg:border-l border-gray-200 dark:border-gray-700 pt-6 lg:pt-0 lg:pl-6">
                    <h3 className="text-xl font-bold mb-2">
                        Progreso general
                        <br/>
                        VCT / PRESENCIALES
                    </h3>
                    <p className="text-sm text-gray-500 mb-2">Cursos {approvedCount}/{allVctCourses.length}</p>
                    <p className={`text-7xl font-bold my-2 ${approvalColor}`}>{`${approvalPercentage}%`}</p>
                    <div className="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-4"> 
                        <div className={`${approvalColor.replace('text-', 'bg-')} h-4 rounded-full`} style={{ width: `${approvalPercentage}%` }}></div>
                    </div>
                </div>
            </Card>
        </section>
    );
};

const NewsSection = ({ news }) => {
    const { currentUser, db, setDb } = useAuth();

    const RoleTag = ({ role }) => {
        const colors = {
            ADMINISTRADOR: 'bg-red-100 text-red-800 dark:bg-red-900/50 dark:text-red-300',
            SUPERVISOR: 'bg-purple-100 text-purple-800 dark:bg-purple-900/50 dark:text-purple-300',
            SOCIO: 'bg-indigo-100 text-indigo-800 dark:bg-indigo-900/50 dark:text-indigo-300',
            ALUMNO: 'bg-blue-100 text-blue-800 dark:bg-blue-900/50 dark:text-blue-300',
        };
        return <span className={`text-xs font-semibold px-2 py-0.5 rounded-full ${colors[role] || 'bg-gray-100 text-gray-800'}`}>{role}</span>;
    };
    
    // This function simulates updating the database state.
    // In a real app, this would trigger an API call.
    const handleReaction = (newsId, reactionType) => {
        if (!currentUser || !db) return;
        
        postDataToSheet('logReaction', { userId: currentUser.id, newsId, reactionType });

        const newDb = JSON.parse(JSON.stringify(db)); // Deep copy
        const newsItem = newDb.news.find(item => item.id === newsId);
        if (!newsItem) return;

        const likes = newsItem.reactions.likes;
        const dislikes = newsItem.reactions.dislikes;
        const otherReaction = reactionType === 'like' ? dislikes : likes;
        const reactionList = reactionType === 'like' ? likes : dislikes;

        // Remove from the other list if present
        const otherIndex = otherReaction.indexOf(currentUser.id);
        if (otherIndex > -1) otherReaction.splice(otherIndex, 1);

        // Toggle in the current list
        const reactionIndex = reactionList.indexOf(currentUser.id);
        if (reactionIndex > -1) {
            reactionList.splice(reactionIndex, 1);
        } else {
            reactionList.push(currentUser.id);
        }
        setDb(newDb); // Update the state
    };

    const ReactionButton = ({ type, newsItem }) => {
        const isLike = type === 'like';
        const reactionList = isLike ? newsItem.reactions.likes : newsItem.reactions.dislikes;
        const reactedByUser = currentUser ? reactionList.includes(currentUser.id) : false;
        const reactionColor = isLike ? 'text-blue-500' : 'text-red-500';
        const icon = isLike 
            ? <svg className={`w-5 h-5 ${reactedByUser ? reactionColor : 'text-gray-500'}`} fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M14 9V5a3 3 0 0 0-3-3l-4 9v11h11.28a2 2 0 0 0 2-1.7l1.38-9a2 2 0 0 0-2-2.3zM7 22H4a2 2 0 0 1-2-2v-7a2 2 0 0 1 2-2h3" /></svg>
            : <svg className={`w-5 h-5 ${reactedByUser ? reactionColor : 'text-gray-500'}`} fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M10 15v4a3 3 0 0 1-3 3l-4-9V2h11.28a2 2 0 0 1 2 1.7l1.38 9a2 2 0 0 1-2 2.3zM7 2H4a2 2 0 0 0-2 2v7a2 2 0 0 0 2 2h3" /></svg>;

        const reactors = reactionList.map(id => db.users.find(u => u.id === id)?.name).filter(Boolean).join(', ');

        return (
            <div className="relative has-tooltip flex items-center gap-1">
                <button onClick={() => handleReaction(newsItem.id, type)} className="p-1 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700 flex items-center gap-1">
                    {icon}
                </button>
                <span className="text-xs font-semibold">{reactionList.length}</span>
                {reactors && (
                    <div className="tooltip absolute bottom-full mb-2 left-1/2 -translate-x-1/2 w-max max-w-xs bg-gray-800 text-white text-xs rounded py-1 px-2 pointer-events-none z-10">
                        {reactors}
                    </div>
                )}
            </div>
        );
    };

    return (
        <section className="mt-10 animate-fade-in">
            <h2 className="text-2xl font-bold mb-4 border-l-4 border-[#00a9e0] pl-4 text-[#0d2235] dark:text-white">Novedades</h2>
            <Card className="p-6 space-y-4">
                {news.length > 0 ? news.map(item => (
                    <div key={item.id} className="border-l-2 border-gray-200 dark:border-gray-700 pl-4">
                        <p className="font-bold">{item.title}</p>
                        <p className="text-gray-600 dark:text-gray-300 text-sm">{item.content}</p>
                        <div className="flex items-center justify-between mt-2">
                            <p className="text-xs text-gray-400">{new Date(item.date + 'T00:00:00').toLocaleDateString()}</p>
                            <div className="flex items-center space-x-4">
                                <ReactionButton type="like" newsItem={item} />
                                <ReactionButton type="dislike" newsItem={item} />
                            </div>
                        </div>
                        <div className="mt-2 flex flex-wrap gap-2">
                            {item.targetRoles.map(role => <RoleTag key={role} role={role} />)}
                        </div>
                    </div>
                )) : <p className="text-gray-500">No hay novedades por el momento.</p>}
            </Card>
        </section>
    );
};

const FaqSection = ({ faqs }) => (
    <section className="mt-10 animate-fade-in">
        <h2 className="text-2xl font-bold mb-4 border-l-4 border-purple-500 pl-4 text-[#0d2235] dark:text-white">Preguntas Frecuentes</h2>
        <Card className="p-6 space-y-4">
            {faqs.map((faq, i) => (
                <details key={i} className="bg-gray-50 dark:bg-gray-800/60 p-4 rounded-lg group transition-colors hover:bg-gray-100 dark:hover:bg-gray-700/70">
                    <summary className="flex justify-between items-center cursor-pointer font-semibold">
                        {faq.question}
                        <svg className="w-5 h-5 ml-2 transition-transform transform details-arrow flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 9l-7 7-7-7" /></svg>
                    </summary>
                    <p className="mt-3 pt-3 border-t border-gray-200 dark:border-gray-700 text-gray-600 dark:text-gray-300">{faq.answer}</p>
                </details>
            ))}
        </Card>
    </section>
);

const InternalTrainingSection = ({ courses }) => (
    <section className="mt-10 animate-fade-in">
        <h2 className="text-2xl font-bold mb-4 border-l-4 border-red-500 pl-4 text-[#0d2235] dark:text-white">Capacitaciones Internas</h2>
        <Card className="p-6 space-y-4">
            {courses.map((course, i) => (
                <details key={i} className="bg-gray-50 dark:bg-gray-800/60 p-4 rounded-lg group transition-colors hover:bg-gray-100 dark:hover:bg-gray-700/70">
                    <summary className="flex justify-between items-center cursor-pointer font-semibold">
                        {course.title}
                        <svg className="w-5 h-5 ml-2 transition-transform transform details-arrow flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 9l-7 7-7-7" /></svg>
                    </summary>
                    <div className="mt-4 pt-4 border-t border-gray-200 dark:border-gray-700">
                        <p className="text-gray-600 dark:text-gray-300 text-sm mb-4">{course.description}</p>
                        <a href={course.videoUrl} target="_blank" rel="noopener noreferrer" className="inline-block bg-[#00a9e0] hover:bg-[#008ac1] text-white font-semibold py-2 px-4 rounded-lg text-sm text-center transition">Ver Video</a>
                    </div>
                </details>
            ))}
        </Card>
    </section>
);

const LinksSection = ({ links }) => (
    <section className="mt-10 animate-fade-in">
        <h2 className="text-2xl font-bold mb-4 border-l-4 border-gray-500 pl-4 text-[#0d2235] dark:text-white">Links de Interés</h2>
        <Card className="p-6">
            <div className="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-4">
                {links.map(link => (
                    <a key={link.name} href={link.url} target="_blank" rel="noopener noreferrer" className="bg-gray-100 dark:bg-gray-800 dark:hover:bg-gray-700 p-2 rounded-lg text-center font-semibold text-gray-700 dark:text-gray-200 transition flex items-center justify-center text-xs sm:text-sm h-16 break-words border border-transparent hover:bg-gray-200 dark:border-gray-600">
                        {link.name}
                    </a>
                ))}
            </div>
        </Card>
    </section>
);

const Calendar = ({ deadline, holidays }) => {
    const [viewDate, setViewDate] = useState(new Date(2025, 7, 10)); // Set to a fixed date for demo consistency
    const [isAnimating, setIsAnimating] = useState(false);
    const holidaySet = useRef(new Set(holidays.map(h => h.date))).current;
    const today = new Date(2025, 7, 10); // Fixed today
    today.setHours(0, 0, 0, 0);
    const deadlineDate = deadline ? new Date(deadline + 'T00:00:00') : null;
    if (deadlineDate) deadlineDate.setHours(0, 0, 0, 0);

    const navigateMonth = (offset) => {
        setIsAnimating(true);
        setTimeout(() => {
            const newDate = new Date(viewDate.getFullYear(), viewDate.getMonth() + offset, 1);
            const minDate = new Date(2023, 0, 1);
            const maxDate = new Date(2027, 11, 31);
            if (newDate >= minDate && newDate <= maxDate) {
                setViewDate(newDate);
            }
            setIsAnimating(false);
        }, 150);
    };
    
    const isNavDisabled = (offset) => {
        const newViewDate = new Date(viewDate.getFullYear(), viewDate.getMonth() + offset, 1);
        const minDate = new Date(2023, 0, 1);
        const maxDate = new Date(2027, 11, 31);
        if (offset < 0) return newViewDate < minDate;
        if (offset > 0) return newViewDate > maxDate;
        return false;
    };
    
    const year = viewDate.getFullYear();
    const month = viewDate.getMonth();
    const firstDayOfMonth = new Date(year, month, 1).getDay();
    const daysInMonth = new Date(year, month + 1, 0).getDate();
    const days = Array.from({ length: firstDayOfMonth }, (_, i) => <div key={`blank-${i}`} />);
    for (let day = 1; day <= daysInMonth; day++) {
        const currentDate = new Date(year, month, day);
        let dayClasses = "w-9 h-9 flex items-center justify-center rounded-full text-sm transition-colors";
        if (currentDate.getTime() === today.getTime()) dayClasses += " bg-[#00a9e0] text-white font-bold";
        else if (deadlineDate && currentDate.getTime() === deadlineDate.getTime()) dayClasses += " bg-red-500 text-white font-bold";
        else if (holidaySet.has(currentDate.toISOString().split('T')[0])) dayClasses += " bg-gray-400 dark:bg-gray-600 text-white";
        else dayClasses += " hover:bg-gray-200 dark:hover:bg-gray-700";
        days.push(<div key={day} className={dayClasses}>{day}</div>);
    }

    const formattedDate = new Date(viewDate).toLocaleDateString('es-AR', { month: 'long', year: 'numeric' });
    const capitalizedDate = formattedDate.charAt(0).toUpperCase() + formattedDate.slice(1).replace(' de ', ' ');
    
    return (
        <Card className="p-6 flex flex-col">
            <h3 className="text-xl font-bold mb-4 text-[#0d2235] dark:text-white">Calendario</h3>
            <div className="flex justify-between items-center mb-4">
                <button onClick={() => navigateMonth(-1)} disabled={isNavDisabled(-1)} className="p-1 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700 disabled:opacity-50">
                    <svg className="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M15 19l-7-7 7-7" /></svg>
                </button>
                <p className="font-semibold capitalize">{capitalizedDate}</p>
                <button onClick={() => navigateMonth(1)} disabled={isNavDisabled(1)} className="p-1 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700 disabled:opacity-50">
                    <svg className="w-5 h-5" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M9 5l7 7-7 7" /></svg>
                </button>
            </div>
            <div className={`grid grid-cols-7 gap-y-2 text-center transition-opacity duration-300 ${isAnimating ? 'opacity-0' : 'opacity-100'}`}>
                {['Do', 'Lu', 'Ma', 'Mi', 'Ju', 'Vi', 'Sá'].map(d => <div key={d} className="font-bold text-xs text-gray-500">{d}</div>)}
                {days}
            </div>
            <div className="mt-auto pt-4 flex items-center justify-center flex-wrap gap-4 text-xs">
                <div className="flex items-center gap-2"><div className="w-3 h-3 rounded-full bg-[#00a9e0] legend-pulse"></div><span>Día Actual</span></div>
                {deadlineDate && <div className="flex items-center gap-2"><div className="w-3 h-3 rounded-full bg-red-500 legend-pulse" style={{animationDelay: '0.5s'}}></div><span>Fecha Límite</span></div>}
                <div className="flex items-center gap-2"><div className="w-3 h-3 rounded-full bg-gray-400 legend-pulse" style={{animationDelay: '1s'}}></div><span>Feriado</span></div>
            </div>
        </Card>
    );
};

const UpcomingEvents = ({ holidays }) => {
    const today = new Date(2025, 7, 10); // Fixed today for demo
    today.setHours(0, 0, 0, 0);
    const upcoming = holidays
        .map(h => ({ ...h, dateObj: new Date(h.date + 'T00:00:00') }))
        .filter(h => h.dateObj >= today)
        .sort((a, b) => a.dateObj.getTime() - b.dateObj.getTime())
        .slice(0, 5);
        
    const typeInfo = {
        'feriado': { text: 'Feriado', classes: 'bg-red-100 text-red-800 dark:bg-red-900/50 dark:text-red-300' },
        'no-laborable': { text: 'No laborable', classes: 'bg-yellow-100 text-yellow-800 dark:bg-yellow-900/50 dark:text-yellow-300' }
    };

    return (
        <Card className="p-6 h-full flex flex-col">
            <h3 className="text-xl font-bold mb-4">Próximos Eventos</h3>
            <ul className="space-y-3">
                {upcoming.map((holiday, i) => {
                    const eventType = typeInfo[holiday.type];
                    return (
                        <li key={i} className="flex items-start gap-3">
                            <div className="flex-shrink-0 mt-1 w-10 h-10 rounded-lg bg-[#00a9e0]/20 text-[#00a9e0] flex flex-col items-center justify-center font-bold">
                                <span className="text-xs">{holiday.dateObj.toLocaleDateString('es-AR', { month: 'short' }).toUpperCase().replace('.', '')}</span>
                                <span className="text-base leading-none">{holiday.dateObj.getDate()}</span>
                            </div>
                            <div>
                                <p className="font-semibold">{holiday.name}</p>
                                <p className="text-sm text-gray-500">
                                    {holiday.dateObj.toLocaleDateString('es-AR', { weekday: 'long' })}
                                    {eventType && <span className={`ml-2 text-xs font-semibold px-2 py-0.5 rounded-full ${eventType.classes}`}>{eventType.text}</span>}
                                </p>
                            </div>
                        </li>
                    )
                })}
            </ul>
        </Card>
    );
};

const OnThisDay = ({ ephemerides }) => {
    const today = new Date(2025, 7, 10); // Fixed today
    const events = ephemerides.filter(e => e.month === today.getMonth() + 1 && e.day === today.getDate()).slice(0, 3);
    return (
        <section className="mt-10 animate-fade-in">
            <h2 className="text-2xl font-bold mb-4 border-l-4 border-gray-500 pl-4 text-[#0d2235] dark:text-white">Un día como hoy...</h2>
            <Card className="p-6">
                {events.length > 0 ? (
                    <ul className='space-y-4'>
                        {events.map((event, i) => (
                            <li key={i} className='flex items-start gap-4'>
                                <div className={`flex-shrink-0 w-12 h-12 rounded-full flex items-center justify-center font-bold text-white text-sm ${event.scope === 'Argentina' ? 'bg-sky-500' : 'bg-gray-500'}`}>{event.year}</div>
                                <div>
                                    <p>{event.description}</p>
                                    <span className={`mt-1 inline-block text-xs font-semibold px-2 py-0.5 rounded-full ${event.scope === 'Argentina' ? 'bg-sky-100 text-sky-800 dark:bg-sky-900/50 dark:text-sky-300' : 'bg-gray-200 text-gray-800 dark:bg-gray-700 dark:text-gray-300'}`}>{event.scope}</span>
                                </div>
                            </li>
                        ))}
                    </ul>
                ) : <p className='text-gray-500'>No hay efemérides para hoy.</p>}
            </Card>
        </section>
    );
};

const LastLoginSection = ({ userId }) => {
    const [lastLoginInfo, setLastLoginInfo] = useState(null);

    useEffect(() => {
        const accessLog = getAccessLogLocal(userId);
        if (accessLog.length > 1) {
            const lastLoginDate = new Date(accessLog[1]);
            const now = new Date();
            const diffMs = now - lastLoginDate;
            const diffHours = diffMs / (1000 * 60 * 60);
            const diffDays = Math.floor(diffHours / 24);

            let message = '';
            if (diffHours < 24) {
                message = "Has estado en este portal hace horas... ¡Gracias por informarte!";
            } else if (diffDays === 1) {
                message = "Ha pasado 1 día...";
            } else {
                message = `¡Han pasado ${diffDays} días!`;
            }
            
            setLastLoginInfo({
                date: lastLoginDate.toLocaleString('es-AR'),
                message: message
            });
        }
    }, [userId]);

    if (!lastLoginInfo) return null;

    return (
        <section className="mt-10 animate-fade-in">
             <h2 className="text-2xl font-bold mb-4 border-l-4 border-gray-500 pl-4 text-[#0d2235] dark:text-white">Último Ingreso</h2>
            <Card className="p-6 text-center">
                <p>La última vez que ingresaste al portal Uni-Central, fue el {lastLoginInfo.date}.</p>
                <p className="font-semibold mt-2">{lastLoginInfo.message}</p>
            </Card>
        </section>
    );
};

const PolicyStatusSection = ({ users }) => {
    const thirtyDaysAgo = new Date();
    thirtyDaysAgo.setDate(thirtyDaysAgo.getDate() - 30);

    const isPolicyExpired = (acceptanceDate) => {
        if (!acceptanceDate) return true; // Pending if never accepted
        return new Date(acceptanceDate) < thirtyDaysAgo;
    };

    return (
        <section className="mt-10 animate-fade-in">
            <h2 className="text-2xl font-bold mb-4 border-l-4 border-orange-500 pl-4 text-[#0d2235] dark:text-white">Estado de Políticas</h2>
            <Card className="p-6">
                <details>
                    <summary className="flex justify-between items-center cursor-pointer font-semibold text-lg">
                        Ver estado de aceptación de políticas de todos los usuarios
                        <svg className="w-5 h-5 ml-2 transition-transform transform details-arrow flex-shrink-0" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 9l-7 7-7-7" /></svg>
                    </summary>
                    <div className="mt-4 pt-4 border-t dark:border-gray-700 space-y-2">
                        {users.sort((a,b) => a.name.localeCompare(b.name)).map(user => {
                            const needsAcceptance = isPolicyExpired(localStorage.getItem(`policy_accepted_${user.id}`));
                            return (
                                <div key={user.id} className="flex justify-between items-center bg-gray-50 dark:bg-gray-800 p-3 rounded-lg">
                                    <div>
                                        <p className="font-semibold">{user.name}</p>
                                        <p className="text-sm text-gray-500">{getRoleDisplayName(user)}</p>
                                    </div>
                                    {needsAcceptance ? (
                                        <span className="text-xs font-bold px-2 py-1 rounded-full bg-yellow-100 text-yellow-800 dark:bg-yellow-900/50 dark:text-yellow-300">Pendiente de Aceptación</span>
                                    ) : (
                                        <span className="text-xs font-bold px-2 py-1 rounded-full bg-green-100 text-green-800 dark:bg-green-900/50 dark:text-green-300">Aceptado</span>
                                    )}
                                </div>
                            )
                        })}
                    </div>
                </details>
            </Card>
        </section>
    );
};


// --- ROLE-BASED VIEW COMPONENTS ---
// These components render the main content area based on the user's role.

const AlumnoView = () => {
    const { currentUser, db } = useAuth();
    // MODIFICATION: Added a guard to prevent errors if currentUser or db is not yet available.
    if (!currentUser || !db) return <Loader />; 
    const courseData = db.courses[currentUser.id] || { total: 0, completed: 0, deadline: '', pendingCourses: [] };
    const progress = courseData.total > 0 ? Math.round((courseData.completed / courseData.total) * 100) : 100;
    const daysLeft = calculateDaysLeft(courseData.deadline);
    const hasVctCourses = db.vctCourses && db.vctCourses[currentUser.id] && db.vctCourses[currentUser.id].length > 0;
    const getProgressMessage = (p) => p >= 100 ? <span className="inline-block animate-wiggle">¡Felicitaciones! 🎉🎊</span> : p >= 80 ? "¡Te falta poco!" : null;

    const StatCard = ({ icon, value, label, color }) => (
        <div className={`bg-${color}-50 dark:bg-${color}-900/50 p-4 rounded-lg flex flex-col items-center justify-center`}>
            {icon}
            <p className={`text-4xl font-bold text-${color}-600 dark:text-${color}-300 mt-2`}>{value}</p>
            <p className="text-sm text-gray-500 mt-1">{label}</p>
        </div>
    );
    
    return (
        <div className="space-y-10 animate-fade-in">
            <div className="grid grid-cols-1 lg:grid-cols-5 gap-6 lg:items-start">
                <Card className="p-6 lg:col-span-3">
                    <h3 className="text-xl font-bold mb-4">Tu Progreso</h3>
                    <div className="grid grid-cols-1 sm:grid-cols-3 gap-4 text-center">
                        <StatCard
                            icon={<svg className="w-8 h-8 text-blue-500" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M13 10V3L4 14h7v7l9-11h-7z" /></svg>}
                            value={courseData.total}
                            label="Cursos Objetivo"
                            color="blue"
                        />
                        <StatCard
                            icon={<svg className="w-8 h-8 text-green-500" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>}
                            value={courseData.completed}
                            label="Realizados"
                            color="green"
                        />
                        <StatCard
                            icon={<svg className="w-8 h-8 text-yellow-500" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>}
                            value={courseData.total - courseData.completed}
                            label="Pendientes"
                            color="yellow"
                        />
                    </div>
                    <div className="mt-6 text-center bg-red-50 dark:bg-red-900/50 p-4 rounded-lg">
                        <p className="text-gray-600 dark:text-gray-300">
                           <svg className="w-6 h-6 inline-block mr-2 animate-shake-gentle text-red-500" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                           Días restantes:
                        </p>
                        <p className="text-4xl font-bold text-red-500 dark:text-red-400">{daysLeft}</p>
                        <p className="text-xs text-gray-500 mt-1">Fecha límite: {new Date(courseData.deadline + 'T00:00:00').toLocaleDateString('es-AR')}</p>
                    </div>
                </Card>
                <div className="lg:col-span-2">
                    <Card className="p-6 flex flex-col items-center justify-center h-full">
                         <h3 className="text-xl font-bold mb-4">Mi Avance General</h3>
                         <SvgProgressCircle progress={progress} />
                         <p className="mt-4 font-semibold text-lg text-gray-700 dark:text-gray-300">
                              {courseData.completed} / {courseData.total} Cursos
                         </p>
                         {getProgressMessage(progress) && <p className="mt-2 text-center text-lg font-semibold">{getProgressMessage(progress)}</p>}
                         {hasVctCourses && <p className="mt-2 text-center font-semibold text-[#00a9e0]">¡Tenés cursos VCT / PRESENCIALES!</p>}
                    </Card>
                </div>
            </div>
             <div>
                <h2 className="text-2xl font-bold mb-4 border-l-4 border-yellow-400 pl-4">Cursos Pendientes</h2>
                <Card className="p-6">
                    <ul className="space-y-3">
                        {courseData.pendingCourses?.length > 0 ? (
                            courseData.pendingCourses.map((course, i) => (
                                <li key={i} className="bg-gray-100 dark:bg-gray-800 p-3 rounded-lg flex items-center">
                                  <svg className="w-5 h-5 mr-3 text-yellow-500" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                                  <span>{course}</span>
                                </li>
                            ))
                        ) : <li className="text-gray-500 bg-gray-100 dark:bg-gray-800 p-4 rounded-lg">¡Felicidades! No tienes cursos pendientes.</li>}
                    </ul>
                </Card>
            </div>
        </div>
    );
};

const SupervisorView = ({ onDownloadPDF }) => {
    const { currentUser, db } = useAuth();
    // MODIFICATION: Added a guard to prevent errors.
    if (!currentUser || !db) return <Loader />;
    const supervisorTeam = db.teams.find(t => t.supervisorId === currentUser.id);
    if (!supervisorTeam) return <Card className="p-6">No tienes un equipo asignado.</Card>;
    const teamMembers = db.users.filter(u => u.teamId === supervisorTeam.id && u.role === 'ALUMNO');
    const allPersonnel = [currentUser, ...teamMembers];
    const totalTeamCourses = allPersonnel.reduce((sum, p) => sum + (db.courses[p.id]?.total || 0), 0);
    const completedTeamCourses = allPersonnel.reduce((sum, p) => sum + (db.courses[p.id]?.completed || 0), 0);
    const teamProgress = totalTeamCourses > 0 ? Math.round((completedTeamCourses / totalTeamCourses) * 100) : 100;

    return (
        <div className="space-y-10 animate-fade-in">
            <h2 className="text-2xl font-bold border-l-4 border-blue-500 pl-4">Tu Progreso Personal</h2>
            <AlumnoView />
            <h2 className="text-2xl font-bold mt-10 border-l-4 border-purple-500 pl-4">Progreso de tu Equipo</h2>
            <div className="grid grid-cols-1 lg:grid-cols-3 gap-6">
                <Card className="lg:col-span-2 p-6">
                    <h3 className="text-xl font-bold mb-4">{supervisorTeam.name}</h3>
                    <div className="space-y-3">
                        {allPersonnel.map(member => {
                             const courseData = db.courses[member.id] || { total: 0, completed: 0 };
                             const progress = courseData.total > 0 ? Math.round((courseData.completed / courseData.total) * 100) : 100;
                             const barColor = progress < 85 ? 'bg-red-500' : 'bg-[#00a9e0]';
                             return (
                                 <div key={member.id} className={`flex items-center justify-between p-4 rounded-lg ${member.id === currentUser.id ? 'bg-blue-50 dark:bg-blue-900/50' : 'bg-gray-50 dark:bg-gray-800'}`}>
                                     <div>
                                         <p className="font-semibold">{member.name}</p>
                                         <p className="text-sm text-gray-500">Cursos: {courseData.completed}/{courseData.total}</p>
                                     </div>
                                     <div className="w-1/3">
                                         <div className="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
                                             <div className={`${barColor} h-2.5 rounded-full`} style={{ width: `${progress}%` }}></div>
                                         </div>
                                         <p className="text-xs text-right mt-1">{progress}%</p>
                                     </div>
                                 </div>
                             )
                        })}
                    </div>
                </Card>
                <Card className="p-6 text-center flex flex-col justify-center items-center">
                    <h3 className="text-xl font-bold mb-4">Progreso General del Equipo</h3>
                    <SvgProgressCircle progress={teamProgress} />
                    <p className="mt-4 font-semibold text-lg text-gray-700 dark:text-gray-300">
                        {completedTeamCourses} / {totalTeamCourses} Cursos
                    </p>
                    <div className="mt-6 w-full space-y-2">
                        <button onClick={onDownloadPDF} className="w-full bg-red-100 text-red-700 dark:bg-red-900/50 dark:text-red-300 font-semibold py-2 px-4 rounded-lg hover:bg-red-200 dark:hover:bg-red-900 transition">Descargar PDF</button>
                        <a href="mailto:jalamo@centralchevrolet.com.ar" className="w-full bg-gray-200 text-gray-800 dark:bg-gray-700 dark:text-gray-200 font-semibold py-2 px-4 rounded-lg flex items-center justify-center gap-2 hover:bg-gray-300 dark:hover:bg-gray-600 transition">
                            Consulta por E-Mail
                        </a>
                    </div>
                </Card>
            </div>
            <TeamVctSection db={db} users={allPersonnel} title="Cursos VCT / PRESENCIALES DEL EQUIPO" />
        </div>
    );
};

// MODIFICATION: This component is now dynamic based on the current date and franchiseMeeting data.
const QuarterlyProgressTimeline = ({ franchiseMeeting }) => {
    // For demo purposes, we fix the current date to be in Q3 2025.
    const today = new Date(2025, 7, 10); // August 10, 2025
    const currentMonth = today.getMonth(); // 7 (August)
    const currentQuarter = Math.floor(currentMonth / 3) + 1; // Q3 = 3

    const quarterData = [
        { name: 'Q1', progress: franchiseMeeting.q1_progress, period: 'Ene-Mar' },
        { name: 'Q2', progress: franchiseMeeting.q2_progress, period: 'Abr-Jun' },
        { name: 'Q3', progress: franchiseMeeting.q3_progress, period: 'Jul-Sep' },
        { name: 'Q4', progress: franchiseMeeting.q4_progress, period: 'Oct-Dic' },
    ];

    const quarters = quarterData.map((q, index) => {
        const quarterNumber = index + 1;
        let status;
        if (quarterNumber < currentQuarter) {
            status = 'completed';
        } else if (quarterNumber === currentQuarter) {
            status = 'in-progress';
        } else {
            status = 'not-started';
        }
        return { ...q, status };
    });
    
    const activeQuarters = quarters.filter(q => q.status === 'completed' || q.status === 'in-progress');
    const annualAverage = activeQuarters.length > 0
        ? Math.round(activeQuarters.reduce((acc, q) => acc + q.progress, 0) / activeQuarters.length)
        : 0;

    const getStatusInfo = (q) => {
        switch(q.status) {
            case 'completed':
                return {
                    icon: <svg className="w-7 h-7 text-green-500" fill="currentColor" viewBox="0 0 20 20"><path fillRule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clipRule="evenodd" /></svg>,
                    text: <p className="text-sm font-bold text-green-600 dark:text-green-400">{q.progress}%</p>
                };
            case 'in-progress':
                return {
                    icon: <svg className="w-7 h-7 text-blue-500 animate-pulse" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>,
                    text: <><p className="text-sm font-bold text-blue-600 dark:text-blue-400">{q.progress}%</p><p className="text-xs text-blue-500">En proceso...</p></>
                };
            case 'not-started':
            default:
                return {
                    icon: <svg className="w-7 h-7 text-gray-400" fill="currentColor" viewBox="0 0 20 20"><path fillRule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zM7 9a1 1 0 000 2h6a1 1 0 100-2H7z" clipRule="evenodd" /></svg>,
                    text: <p className="text-xs text-gray-500">No iniciado</p>
                };
        }
    }

    return (
      <Card className="p-6">
        <h3 className="text-xl font-bold mb-6 text-[#0d2235] dark:text-white">Progreso Anual - Central Autos</h3>
        <div className="flex items-center relative mb-16">
            <div className="absolute top-1/2 left-0 w-full h-1 bg-gray-200 dark:bg-gray-700 -translate-y-1/2"></div>
            <div className="flex justify-between w-full">
                {quarters.map((q) => {
                    const statusInfo = getStatusInfo(q);
                    return (
                        <div key={q.name} className="z-10 flex flex-col items-center">
                            <div className="bg-white dark:bg-[#1f2937] p-0.5 rounded-full">
                                {statusInfo.icon}
                            </div>
                            <div className="absolute top-10 text-center w-24">
                                <p className="font-bold text-sm">{q.name}</p>
                                <p className="text-xs text-gray-500">{q.period}</p>
                                <div className="mt-1 h-10 flex flex-col items-center justify-start">{statusInfo.text}</div>
                            </div>
                        </div>
                    );
                })}
            </div>
        </div>
        <div className="text-center mt-6 pt-6 border-t border-gray-200 dark:border-gray-700">
            <p className="text-gray-500 uppercase text-xs font-bold tracking-wider">Acumulado Anual</p>
            <p className="text-4xl font-bold text-[#0d2235] dark:text-white mt-1">{annualAverage}%</p>
        </div>
      </Card>
    );
};

// MODIFICATION: New CX (Customer Experience) section components
const StarRatingDisplay = ({ rating, totalReviews }) => {
    const fullStars = Math.floor(rating);
    const halfStar = rating % 1 >= 0.5;
    const emptyStars = 5 - fullStars - (halfStar ? 1 : 0);

    return (
        <div className="flex items-center justify-center">
            <div className="flex text-yellow-400 text-2xl">
                {[...Array(fullStars)].map((_, i) => <span key={`full-${i}`}>&#9733;</span>)}
                {halfStar && <span key="half">&#9734;</span>} {/* Using empty star for half for simplicity */}
                {[...Array(emptyStars)].map((_, i) => <span key={`empty-${i}`} className="text-gray-300 dark:text-gray-600">&#9733;</span>)}
            </div>
            <span className="ml-2 text-sm font-bold text-gray-700 dark:text-gray-200">{rating.toFixed(1)}</span>
            <span className="ml-1 text-xs text-gray-500">({totalReviews} opiniones)</span>
        </div>
    );
};

const CxSocioView = ({ surveyData }) => {
    if (!surveyData || surveyData.length === 0) return null;

    const totalReviews = surveyData.length;
    const avgSatisfaction = surveyData.reduce((acc, curr) => acc + curr.satisfaction, 0) / totalReviews;
    const avgRecommend = surveyData.reduce((acc, curr) => acc + curr.recommend, 0) / totalReviews;

    return (
        <section className="mt-10 animate-fade-in">
            <h2 className="text-2xl font-bold mb-4 border-l-4 border-cyan-500 pl-4 text-[#0d2235] dark:text-white">Calificación del portal Uni-Central</h2>
            <Card className="p-6 grid grid-cols-1 md:grid-cols-2 gap-6">
                <div className="text-center">
                    <h3 className="font-bold text-lg mb-2">Satisfacción General<br/>portal Uni-Central</h3>
                    <StarRatingDisplay rating={avgSatisfaction} totalReviews={totalReviews} />
                </div>
                <div className="text-center">
                    <h3 className="font-bold text-lg mb-2">Recomendación del portal<br/>Uni-Central</h3>
                    <StarRatingDisplay rating={avgRecommend} totalReviews={totalReviews} />
                </div>
            </Card>
        </section>
    );
};

const CxAdminView = ({ surveyData, users }) => {
    if (!surveyData || surveyData.length === 0) return null;

    const totalReviews = surveyData.length;
    const avgSatisfaction = surveyData.reduce((acc, curr) => acc + curr.satisfaction, 0) / totalReviews;
    const avgRecommend = surveyData.reduce((acc, curr) => acc + curr.recommend, 0) / totalReviews;
    
    const botResponses = surveyData.filter(r => r.botHelpful !== null);
    const botYes = botResponses.filter(r => r.botHelpful === true).length;
    const botNo = botResponses.filter(r => r.botHelpful === false).length;
    const botYesPercent = botResponses.length > 0 ? (botYes / botResponses.length) * 100 : 0;
    const botNoPercent = botResponses.length > 0 ? (botNo / botResponses.length) * 100 : 0;

    const feedbacks = surveyData.filter(r => r.feedback && r.feedback.trim() !== "");

    const getUserName = (userId) => users.find(u => u.id === userId)?.name || 'Usuario Anónimo';

    return (
        <section className="mt-10 animate-fade-in">
            <h2 className="text-2xl font-bold mb-4 border-l-4 border-cyan-500 pl-4 text-[#0d2235] dark:text-white">Panel de Experiencia (CX)</h2>
            <div className="grid grid-cols-1 lg:grid-cols-2 gap-6">
                <div className="space-y-6">
                    <Card className="p-6">
                        <h3 className="font-bold text-lg mb-2 text-center">Métricas Principales</h3>
                        <details className="group">
                            <summary className="flex justify-center items-center cursor-pointer p-2 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-800">
                                <div className="text-center">
                                    <h4 className="font-semibold">Satisfacción General</h4>
                                    <StarRatingDisplay rating={avgSatisfaction} totalReviews={totalReviews} />
                                </div>
                                <svg className="w-5 h-5 ml-2 transition-transform transform details-arrow flex-shrink-0 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 9l-7 7-7-7" /></svg>
                            </summary>
                            <ul className="mt-2 pt-2 border-t dark:border-gray-700 text-sm space-y-1 max-h-40 overflow-y-auto">
                                {surveyData.map((s, i) => <li key={i} className="flex justify-between"><span>{getUserName(s.userId)}:</span> <span className="font-bold">{s.satisfaction} ★</span></li>)}
                            </ul>
                        </details>
                        <details className="group mt-4">
                             <summary className="flex justify-center items-center cursor-pointer p-2 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-800">
                                <div className="text-center">
                                    <h4 className="font-semibold">Nivel de Recomendación</h4>
                                    <StarRatingDisplay rating={avgRecommend} totalReviews={totalReviews} />
                                </div>
                                <svg className="w-5 h-5 ml-2 transition-transform transform details-arrow flex-shrink-0 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 9l-7 7-7-7" /></svg>
                            </summary>
                             <ul className="mt-2 pt-2 border-t dark:border-gray-700 text-sm space-y-1 max-h-40 overflow-y-auto">
                                {surveyData.map((s, i) => <li key={i} className="flex justify-between"><span>{getUserName(s.userId)}:</span> <span className="font-bold">{s.recommend} ★</span></li>)}
                            </ul>
                        </details>
                    </Card>
                    <Card className="p-6">
                        <details className="group">
                            <summary className="flex justify-between items-center cursor-pointer p-2 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-800">
                                <h3 className="font-bold text-lg text-center flex-grow">Utilidad de Uni-Bot</h3>
                                <svg className="w-5 h-5 ml-2 transition-transform transform details-arrow flex-shrink-0 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 9l-7 7-7-7" /></svg>
                            </summary>
                            <div className="mt-2 pt-2 border-t dark:border-gray-700">
                                <div className="space-y-2">
                                    <div className="flex justify-between items-center text-sm"><span className="font-semibold">Sí</span><span>{botYes} ({botYesPercent.toFixed(0)}%)</span></div>
                                    <div className="w-full bg-gray-200 rounded-full h-4 dark:bg-gray-700"><div className="bg-green-500 h-4 rounded-full" style={{ width: `${botYesPercent}%` }}></div></div>
                                </div>
                                <div className="space-y-2 mt-3">
                                    <div className="flex justify-between items-center text-sm"><span className="font-semibold">No</span><span>{botNo} ({botNoPercent.toFixed(0)}%)</span></div>
                                    <div className="w-full bg-gray-200 rounded-full h-4 dark:bg-gray-700"><div className="bg-red-500 h-4 rounded-full" style={{ width: `${botNoPercent}%` }}></div></div>
                                </div>
                                <ul className="mt-2 pt-2 border-t dark:border-gray-700 text-sm space-y-1 max-h-40 overflow-y-auto">
                                    {botResponses.map((s, i) => <li key={i} className="flex justify-between"><span>{getUserName(s.userId)}:</span> <span className={`font-bold ${s.botHelpful ? 'text-green-500' : 'text-red-500'}`}>{s.botHelpful ? 'Sí' : 'No'}</span></li>)}
                                </ul>
                            </div>
                        </details>
                    </Card>
                </div>
                <Card className="p-6">
                    <details className="group">
                        <summary className="flex justify-between items-center cursor-pointer p-2 rounded-lg hover:bg-gray-100 dark:hover:bg-gray-800">
                            <h3 className="font-bold text-lg text-center flex-grow">Comentarios y Sugerencias</h3>
                            <svg className="w-5 h-5 ml-2 transition-transform transform details-arrow flex-shrink-0 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 9l-7 7-7-7" /></svg>
                        </summary>
                        <div className="mt-2 pt-2 border-t dark:border-gray-700 space-y-3 max-h-80 overflow-y-auto pr-2">
                            {feedbacks.length > 0 ? feedbacks.map((fb, i) => (
                                <div key={i} className="bg-gray-50 dark:bg-gray-800 p-3 rounded-lg text-sm">
                                    <p className="italic">"{fb.feedback}"</p>
                                    <p className="text-xs text-gray-400 text-right mt-1">{getUserName(fb.userId)} - {new Date(fb.timestamp).toLocaleString('es-AR')}</p>
                                </div>
                            )) : <p className="text-center text-gray-500">No hay comentarios.</p>}
                        </div>
                    </details>
                </Card>
            </div>
        </section>
    );
};

const SocioView = ({ onDownloadPDF }) => {
    const { db } = useAuth();
    // MODIFICATION: Added a guard to prevent errors.
    if (!db) return <Loader />;
    const teamsWithProgress = db.teams.map(team => {
        const supervisor = db.users.find(u => u.id === team.supervisorId);
        const members = db.users.filter(u => u.teamId === team.id);
        const teamProgress = members.length > 0
            ? Math.round(members.reduce((sum, person) => {
                const courseData = db.courses[person.id] || { total: 0, completed: 0 };
                return sum + (courseData.total > 0 ? (courseData.completed / courseData.total) : 1);
              }, 0) / members.length * 100)
            : 100;

        return { ...team, allPersonnel: members, teamProgress, supervisor };
    }).sort((a, b) => a.teamProgress - b.teamProgress);

    const { franchiseMeeting } = db;
    const meetingComplianceColor = franchiseMeeting.compliancePercentage >= 90 ? 'text-green-500 dark:text-green-400' : franchiseMeeting.compliancePercentage >= 80 ? 'text-yellow-500 dark:text-yellow-400' : 'text-red-500 dark:text-red-400';
    const categoryText = franchiseMeeting.compliancePercentage > 85 ? 'Categoría A' : 'Categoría B';

    const EligibilityBadge = ({ status }) => {
        const isEligible = status === 'ELEGIBLE';
        const config = {
            'ELEGIBLE': 'bg-green-100 text-green-800 dark:bg-green-900/50 dark:text-green-300',
            'NO ELEGIBLE': 'bg-red-100 text-red-800 dark:bg-red-900/50 dark:text-red-300'
        };
        const statusText = status.charAt(0).toUpperCase() + status.slice(1).toLowerCase();
        return <span className={`px-3 py-1 text-xs font-bold rounded-full ${isEligible ? config['ELEGIBLE'] : config['NO ELEGIBLE']}`}>{statusText}</span>;
    };

    const MetricItem = ({ label, value }) => {
        const color = value >= 95 ? 'text-green-600 dark:text-green-400' : 'text-yellow-600 dark:text-yellow-400';
        return (
            <div className="bg-gray-50 dark:bg-gray-800/60 p-3 rounded-lg text-center">
                <p className="text-xs text-gray-500 dark:text-gray-400 font-semibold">{label}</p>
                <p className={`text-2xl font-bold ${color}`}>{value}%</p>
            </div>
        );
    };
    
    return (
        <div className="animate-fade-in space-y-6">
            <div className="grid grid-cols-1 lg:grid-cols-3 gap-6">
                <div className="lg:col-span-2 space-y-6">
                    <Card className="p-6">
                        <h3 className="text-xl font-bold mb-4">Vista General de Equipos</h3>
                        <div className="space-y-4">
                            {teamsWithProgress.map(team => {
                                const memberCount = team.allPersonnel.filter(m => m.role === 'ALUMNO').length;
                                const sortedPersonnel = [...team.allPersonnel].sort((a, b) => {
                                    if (a.role === 'SUPERVISOR') return -1;
                                    if (b.role === 'SUPERVISOR') return 1;
                                    return a.name.localeCompare(b.name);
                                });
                                return (
                                <details key={team.id} className="bg-gray-50 dark:bg-gray-800 p-4 rounded-lg group transition-colors hover:bg-gray-100 dark:hover:bg-gray-700/70">
                                    <summary className="flex justify-between items-center cursor-pointer">
                                        <div className="flex-1">
                                            <h4 className="font-bold">{team.name}</h4>
                                            <div className="text-sm text-gray-500">
                                                <p>Sup: {team.supervisor?.name || 'N/A'}</p>
                                                <p>{memberCount} {memberCount === 1 ? 'alumno' : 'alumnos'}</p>
                                            </div>
                                        </div>
                                        <div className="text-right flex items-center gap-4">
                                            <div className="text-right">
                                                <p className={`text-3xl font-bold ${team.teamProgress < 85 ? 'text-red-500' : 'text-[#00a9e0]'}`}>{team.teamProgress}%</p>
                                                <p className="text-sm text-gray-500 -mt-1">progreso</p>
                                            </div>
                                            <svg className="w-5 h-5 ml-2 transition-transform transform details-arrow flex-shrink-0 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M19 9l-7 7-7-7" /></svg>
                                        </div>
                                    </summary>
                                    <ul className="mt-4 pt-4 border-t dark:border-gray-700 space-y-2">
                                      {sortedPersonnel.map(member => {
                                        const courseData = db.courses[member.id] || { total: 0, completed: 0 };
                                        const progress = courseData.total > 0 ? Math.round((courseData.completed / courseData.total) * 100) : 100;
                                        const isSupervisor = member.role === 'SUPERVISOR';
                                        const barColor = progress < 85 ? 'bg-red-500' : 'bg-[#00a9e0]';
                                        return (
                                            <li key={member.id} className={`flex items-center justify-between p-3 rounded-md ${isSupervisor ? 'bg-blue-50 dark:bg-blue-900/40' : 'bg-gray-100 dark:bg-gray-700/50'}`}>
                                                <div>
                                                    <p className="font-semibold">{member.name} {isSupervisor && <span className="text-xs font-semibold text-blue-600 dark:text-blue-300">(Sup.)</span>}</p>
                                                    <p className="text-sm text-gray-500">Cursos: {courseData.completed}/{courseData.total}</p>
                                                </div>
                                                <div className="w-1/3">
                                                    <div className="w-full bg-gray-200 dark:bg-gray-600 rounded-full h-2.5">
                                                        <div className={`${barColor} h-2.5 rounded-full`} style={{ width: `${progress}%` }}></div>
                                                    </div>
                                                    <p className="text-xs text-right mt-1 font-semibold">{progress}%</p>
                                                </div>
                                            </li>
                                        )
                                      })}
                                    </ul>
                                </details>
                            )})}
                        </div>
                    </Card>
                    <TeamVctSection db={db} users={db.users.filter(u => u.role === 'ALUMNO' || u.role === 'SUPERVISOR')} title="Resumen de Cursos VCT / PRESENCIALES" />
                </div>
                <div className="lg:col-span-1 space-y-6">
                    <Card className="p-6">
                        <h3 className="text-xl font-bold mb-4 text-center text-[#0d2235] dark:text-white">Franchise Meeting</h3>
                        <p className="text-sm text-center text-gray-500 -mt-3 mb-4">Cumplimiento Universidad Chevrolet</p>

                        <div className="grid grid-cols-[1fr_auto_1fr] items-center justify-items-center my-4 gap-x-4">
                            <div className="text-center">
                                <div className={`flex justify-center items-baseline ${meetingComplianceColor}`}>
                                    <span className="text-6xl font-bold">{franchiseMeeting.compliancePercentage}</span>
                                    <span className="text-3xl font-bold">%</span>
                                </div>
                                <p className={`text-lg font-semibold ${meetingComplianceColor} mt-1`}>progreso</p>
                            </div>
                            <div className="h-20 w-px bg-gray-300 dark:bg-gray-600"></div>
                            <div className="text-center">
                                <p className="text-6xl font-bold text-gray-700 dark:text-gray-200 flex items-baseline justify-center">5
                                    <span className="text-3xl font-normal ml-2">puntos</span>
                                </p>
                                <p className="text-xl font-bold text-gray-700 dark:text-gray-200 mt-1">{categoryText}</p>
                            </div>
                        </div>

                        <hr className="my-4 dark:border-gray-600" />
                        
                        <div className="grid grid-cols-2 gap-3 my-4">
                            <MetricItem label="WBT Ventas" value={franchiseMeeting.salesWbt} />
                            <MetricItem label="VCT Ventas" value={franchiseMeeting.salesVct} />
                            <MetricItem label="WBT Liderazgo" value={franchiseMeeting.leadershipWbt} />
                            <MetricItem label="VCT Liderazgo" value={franchiseMeeting.leadershipVct} />
                        </div>
                        
                        <div className="space-y-3 text-left">
                            <div className="flex justify-between items-center bg-gray-50 dark:bg-gray-800/60 p-3 rounded-lg">
                                <span className="font-semibold text-sm">Elegibilidad Permanente</span>
                                <EligibilityBadge status={franchiseMeeting.permanentEligibility} />
                            </div>
                            <div className="flex justify-between items-center bg-gray-50 dark:bg-gray-800/60 p-3 rounded-lg">
                                <span className="font-semibold text-sm">Elegibilidad Mensual</span>
                                <EligibilityBadge status={franchiseMeeting.monthlyEligibility} />
                            </div>
                        </div>

                        {franchiseMeeting.notes && franchiseMeeting.notes !== '(opcional)' &&
                          <div className="mt-4 text-left">
                              <p className="font-semibold text-sm text-gray-600 dark:text-gray-300">Notas:</p>
                              <p className="text-sm text-gray-600 dark:text-gray-400 bg-gray-50 dark:bg-gray-800/60 p-2 rounded-lg border-l-2 border-gray-300 dark:border-gray-500 pl-3">{franchiseMeeting.notes}</p>
                          </div>
                        }
                        
                        <p className="text-xs text-gray-400 text-center mt-4">Última Actualización: {new Date(franchiseMeeting.lastUpdate + 'T00:00:00').toLocaleDateString('es-AR')}</p>
                    </Card>

                    {/* MODIFICATION: Pass the entire franchiseMeeting object */}
                    <QuarterlyProgressTimeline franchiseMeeting={franchiseMeeting} />

                    <div className="w-full space-y-2">
                        <button onClick={onDownloadPDF} className="w-full bg-red-100 text-red-700 dark:bg-red-900/50 dark:text-red-300 font-semibold py-2 px-4 rounded-lg flex items-center justify-center gap-2 hover:bg-red-200 dark:hover:bg-red-900 transition">
                            <svg className="w-4 h-4" fill="currentColor" viewBox="0 0 20 20"><path fillRule="evenodd" d="M4 4a2 2 0 012-2h4.586A2 2 0 0112 2.586L15.414 6A2 2 0 0116 7.414V16a2 2 0 01-2 2H6a2 2 0 01-2-2V4zm2 6a1 1 0 011-1h6a1 1 0 110 2H7a1 1 0 01-1-1zm1 3a1 1 0 100 2h6a1 1 0 100-2H7z" clipRule="evenodd"></path></svg>
                            Descargar PDF
                        </button>
                         <a href="mailto:jalamo@centralchevrolet.com.ar" className="w-full bg-gray-200 text-gray-800 dark:bg-gray-700 dark:text-gray-200 font-semibold py-2 px-4 rounded-lg flex items-center justify-center gap-2 hover:bg-gray-300 dark:hover:bg-gray-600 transition">
                            Consulta por E-Mail
                        </a>
                    </div>
                </div>
            </div>
            <CxSocioView surveyData={db.surveyData} />
        </div>
    );
};

const AdminView = ({ handleImpersonate, onDownloadPDF, onDownloadExcel }) => {
    const { currentUser, db } = useAuth();
    // Default to a non-admin user for the impersonation dropdown
    const defaultImpersonateUser = db?.users.find(u => u.role !== 'ADMINISTRADOR');
    const [impersonateId, setImpersonateId] = useState(defaultImpersonateUser?.id || '');

    // MODIFICATION: Added a guard to prevent errors.
    if (!currentUser || !db) return <Loader />;

    return (
        <div className="animate-fade-in space-y-10">
            <Card className="p-6">
                <h3 className="text-xl font-bold mb-4">Panel de Administración</h3>
                <div className="grid grid-cols-1 md:grid-cols-2 gap-4">
                    <div>
                        <h4 className="font-semibold mb-2">Ver como otro usuario</h4>
                        <div className="flex gap-2">
                            <select value={impersonateId} onChange={e => setImpersonateId(e.target.value)} className="w-full bg-gray-100 border rounded-lg px-4 py-2 dark:bg-gray-700 dark:border-gray-600">
                                {db.users.filter(u => u.id !== currentUser.id).sort((a, b) => a.name.localeCompare(b.name)).map(u => <option key={u.id} value={u.id}>{u.name} ({getRoleDisplayName(u)})</option>)}
                            </select>
                            <button onClick={() => handleImpersonate(impersonateId)} className="bg-[#00a9e0] hover:bg-[#008ac1] text-white font-semibold py-2 px-6 rounded-lg">Ver</button>
                        </div>
                    </div>
                    <div>
                      <h4 className="font-semibold mb-2">Descargar Reportes</h4>
                      <div className="flex gap-2">
                        <button onClick={onDownloadPDF} className="flex-1 bg-red-100 hover:bg-red-200 text-red-700 dark:bg-red-900/50 dark:text-red-300 dark:hover:bg-red-900 font-semibold py-2 px-4 rounded-lg">Descargar PDF</button>
                        <button onClick={onDownloadExcel} className="flex-1 bg-green-100 hover:bg-green-200 text-green-700 dark:bg-green-900/50 dark:text-green-300 dark:hover:bg-green-900 font-semibold py-2 px-4 rounded-lg">Descargar Excel</button>
                      </div>
                    </div>
                </div>
            </Card>
            <CxAdminView surveyData={db.surveyData} users={db.users} />
            <PolicyStatusSection users={db.users} />
            <SocioView onDownloadPDF={onDownloadPDF} />
        </div>
    );
};

// --- CORE COMPONENTS (LOGIN, DASHBOARD, APP) ---
// These are the top-level components that structure the application flow.

const LoginScreen = ({ onLogin, error, dbConfig }) => {
  const [userId, setUserId] = useState('');
  const handleLoginClick = () => onLogin(userId.trim());
  const handleKeyPress = (e) => e.key === 'Enter' && handleLoginClick();
  
  return (
    <div className="min-h-screen flex flex-col items-center justify-center p-4 bg-[#0d2235] relative overflow-hidden">
      <div className="absolute w-[600px] h-[600px] rounded-[40%] bg-[#00a9e0]/10 animate-rotate -top-[200px] -right-[200px]" />
      <div className="absolute w-[600px] h-[600px] rounded-[40%] bg-[#00a9e0]/10 animate-rotate-reverse -bottom-[250px] -left-[250px]" />
      <div className="w-full max-w-md text-center z-10">
        <div className="bg-white/90 backdrop-blur-sm p-8 rounded-2xl shadow-2xl">
          <h1 className="text-5xl sm:text-6xl font-bold text-[#0d2235] mb-2 title-shimmer" style={{ textShadow: '2px 2px 10px rgba(0,0,0,0.2)' }}>
            Uni<span style={{ color: '#00a9e0' }}>-</span>Central
          </h1>
          <div className="text-gray-500 mb-8 text-sm">
            {dbConfig.login_description.split('\n').map((line, i) => <p key={i}>{line}</p>)}
          </div>
          <input type="text" placeholder="Ingrese su ID" value={userId} onChange={(e) => setUserId(e.target.value)} onKeyPress={handleKeyPress} className="w-full bg-gray-100 border border-gray-300 rounded-lg px-4 py-3 text-gray-800 focus:outline-none focus:ring-2 focus:ring-[#00a9e0]" />
          <button onClick={handleLoginClick} className="w-full bg-[#00a9e0] hover:bg-[#008ac1] text-white font-bold py-3 px-4 rounded-lg mt-6">Ingresar</button>
          {error && <div className="mt-4 p-3 bg-red-100 text-red-700 rounded-lg text-sm">{error}</div>}
        </div>
        <div className="mt-8 flex justify-center items-center space-x-6">
            <a href="https://www.chevroletcentralautos.com.ar/" target="_blank" rel="noopener noreferrer" className="text-gray-400 hover:text-white transition">
                <svg className="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.95-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z"/></svg>
            </a>
            <a href="https://www.facebook.com/chevrolet.centralautos" target="_blank" rel="noopener noreferrer" className="text-gray-400 hover:text-white transition">
                <svg className="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M5 3h14a2 2 0 0 1 2 2v14a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2m13 2h-2.5A3.5 3.5 0 0 0 12 8.5V11h-2v3h2v7h3v-7h2.5l.5-3H15v-2a.5.5 0 0 1 .5-.5H18V5Z"/></svg>
            </a>
            <a href="https://www.instagram.com/chevrolet.centralautos/" target="_blank" rel="noopener noreferrer" className="text-gray-400 hover:text-white transition">
                <svg className="w-6 h-6" fill="currentColor" viewBox="0 0 24 24"><path d="M7.8 2h8.4C19.4 2 22 4.6 22 7.8v8.4a5.8 5.8 0 0 1-5.8 5.8H7.8C4.6 22 2 19.4 2 16.2V7.8A5.8 5.8 0 0 1 7.8 2m-.2 2A3.6 3.6 0 0 0 4 7.6v8.8C4 18.39 5.61 20 7.6 20h8.8a3.6 3.6 0 0 0 3.6-3.6V7.6C20 5.61 18.39 4 16.4 4H7.6m9.65 1.5a1.25 1.25 0 0 1 1.25 1.25A1.25 1.25 0 0 1 17.25 8 1.25 1.25 0 0 1 16 6.75a1.25 1.25 0 0 1 1.25-1.25M12 7a5 5 0 0 1 5 5 5 5 0 0 1-5 5 5 5 0 0 1-5-5 5 5 0 0 1 5-5m0 2a3 3 0 0 0-3 3 3 3 0 0 0 3 3 3 3 0 0 0 3-3 3 3 0 0 0-3-3Z"/></svg>
            </a>
        </div>
      </div>
      <footer className="absolute bottom-4 text-center text-gray-400 text-xs z-10">
        {dbConfig.footer_credits.split('\n').map((line, i) => <p key={i}>{line}</p>)}
      </footer>
    </div>
  );
};

const Header = ({ onHelpClick, onLogoutRequest }) => {
    const { currentUser, originalUser, returnToAdmin, db } = useAuth();
    const [clock, setClock] = useState(new Date());
    const [isNotificationsOpen, setNotificationsOpen] = useState(false);
    const [notifications, setNotifications] = useState([]);
    const notificationsRef = useRef(null);
    const title = "Uni-Central";

    useEffect(() => {
        const timerId = setInterval(() => setClock(new Date()), 1000);
        return () => clearInterval(timerId);
    }, []);

    useEffect(() => {
        if (db && currentUser) setNotifications(generateNotifications(db, currentUser));
    }, [db, currentUser]);
    
    // Close notifications dropdown if clicking outside
    useEffect(() => {
      const handleClickOutside = (event) => {
        if (notificationsRef.current && !notificationsRef.current.contains(event.target)) {
          setNotificationsOpen(false);
        }
      };
      document.addEventListener("mousedown", handleClickOutside);
      return () => document.removeEventListener("mousedown", handleClickOutside);
    }, [notificationsRef]);

    if (!currentUser || !db) return null;

    const notificationCount = notifications.filter(n => n.unread).length;

    const handleNotificationToggle = () => {
        const willBeOpen = !isNotificationsOpen;
        setNotificationsOpen(willBeOpen);

        // Mark as read when opening
        if (willBeOpen && notificationCount > 0) {
            markNotificationsAsRead(notifications.filter(n => n.unread).map(n => n.id));
            // Update UI immediately
            setNotifications(prev => prev.map(n => ({...n, unread: false })));
        }
    };

    const formatDateTime = (date) => {
        const dayOfWeek = new Intl.DateTimeFormat('es-AR', { weekday: 'long' }).format(date);
        const datePart = new Intl.DateTimeFormat('es-AR', { day: '2-digit', month: '2-digit', year: 'numeric' }).format(date);
        const timePart = new Intl.DateTimeFormat('es-AR', { hour: '2-digit', minute: '2-digit' }).format(date);
        return `Hoy es ${dayOfWeek.charAt(0).toUpperCase() + dayOfWeek.slice(1)} ${datePart}. ${timePart}`;
    };

    return (
        <React.Fragment>
            <header className="bg-white/80 dark:bg-[#1f2937]/80 backdrop-blur-sm sticky top-0 z-30 shadow-sm border-b border-gray-200 dark:border-gray-700">
                <div className="container mx-auto px-4 sm:px-6 lg:px-8">
                    <div className="flex items-center justify-between h-16">
                        <div className="flex items-center space-x-4">
                            <div className="font-bold text-2xl md:text-4xl text-[#0d2235] dark:text-white whitespace-nowrap">
                                {title.split('').map((letter, index) => (
                                    <span key={index} className="animated-letter-lift" style={{ animationDelay: `${index * 0.07}s` }}>
                                        {letter === '-' ? <span className="text-[#00a9e0]">{letter}</span> : letter}
                                    </span>
                                ))}
                            </div>
                            <div className="hidden lg:block text-sm text-gray-500">{formatDateTime(clock)}</div>
                        </div>
                        <div className="flex items-center space-x-2 sm:space-x-4">
                            <div className="hidden sm:block text-right leading-tight">
                                <div className="font-semibold text-gray-700 dark:text-gray-200">{currentUser.name}</div>
                                <div className="text-xs text-gray-500">{getRoleDisplayName(currentUser)}</div>
                            </div>
                            <div className="relative" ref={notificationsRef}>
                                <button onClick={handleNotificationToggle} className="relative p-2 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700 transition" aria-label="Notificaciones">
                                    <svg className="w-6 h-6 text-gray-600 dark:text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M15 17h5l-1.4-1.4a2 2 0 01-.6-1.4V11a6 6 0 00-4-5.6V5a2 2 0 10-4 0v.4A6 6 0 006 11v3.2c0 .5-.2 1-.6 1.4L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" /></svg>
                                    {notificationCount > 0 && <span className="absolute top-1 right-1 block h-5 w-5 rounded-full bg-red-500 text-white text-xs flex items-center justify-center">{notificationCount}</span>}
                                </button>
                                {isNotificationsOpen && (
                                    <div className="fixed sm:absolute top-16 sm:top-auto left-4 right-4 sm:left-auto sm:right-0 sm:mt-2 sm:w-80 bg-white dark:bg-gray-800 rounded-lg shadow-xl border dark:border-gray-700 overflow-hidden animate-fade-in">
                                        <div className="p-3 font-bold text-sm border-b dark:border-gray-700">Notificaciones</div>
                                        {notifications.length > 0 ? (
                                            <ul className="py-1 max-h-80 overflow-y-auto">{notifications.map(n => <li key={n.id} className="px-3 py-2 text-sm flex items-center gap-3"><span className={`w-2 h-2 rounded-full flex-shrink-0 ${n.unread ? 'bg-blue-500' : 'bg-transparent'}`}></span><span className="flex-grow">{n.title}</span></li>)}</ul>
                                        ) : <p className="p-3 text-sm text-gray-500">No hay notificaciones.</p>}
                                    </div>
                                )}
                            </div>
                            <button onClick={onHelpClick} className="p-2 rounded-full hover:bg-gray-200 dark:hover:bg-gray-700 transition" aria-label="Modo de uso">
                                <svg className="w-6 h-6 text-gray-600 dark:text-gray-300" fill="none" viewBox="0 0 24 24" stroke="currentColor"><path strokeLinecap="round" strokeLinejoin="round" strokeWidth="2" d="M8.2 9c.5-1.2 2-2 3.8-2 2.2 0 4 1.3 4 3 0 1.4-1.3 2.6-3 2.9-.5.1-1 .5-1 1.1m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" /></svg>
                            </button>
                            <button onClick={onLogoutRequest} className="bg-red-500 hover:bg-red-600 text-white font-semibold py-2 px-4 rounded-lg text-sm">Salir</button>
                        </div>
                    </div>
                </div>
            </header>
            {originalUser && <div className="bg-yellow-400 text-yellow-900 font-bold p-3 text-center sticky top-16 z-20">Estás viendo como {currentUser.name}. <button onClick={returnToAdmin} className="underline">Volver a mi vista</button></div>}
        </React.Fragment>
    );
};

const Footer = ({ lastUpdate, credits }) => (
    <footer className="mt-10 text-center py-6 text-xs text-gray-400 border-t border-gray-200 dark:border-gray-700">
        <p>Última actualización: {new Date(lastUpdate + 'T00:00:00').toLocaleDateString('es-AR')}</p>
        <p className="mt-1">{credits}</p>
    </footer>
);

const FloatingActionButtons = ({ onBotClick }) => {
    // Custom hook for periodic animations on desktop
    const usePeriodicAnimation = (intervalTime) => {
        const [isExpanded, setIsExpanded] = useState(true);
        useEffect(() => {
            if (window.innerWidth < 768) return; // Desktop only
            const interval = setInterval(() => {
                setIsExpanded(false);
                const timeout = setTimeout(() => setIsExpanded(true), 400);
                return () => clearTimeout(timeout);
            }, intervalTime);
            return () => clearInterval(interval);
        }, [intervalTime]);
        return isExpanded;
    };

    const isUcExpanded = usePeriodicAnimation(15000);
    const isConsultasExpanded = usePeriodicAnimation(17000);
    const isBotNameVisible = usePeriodicAnimation(10000);
    
    return (
        <div className='fixed bottom-6 right-6 z-50 flex flex-col items-end gap-3'>
            {ai && (
                <button onClick={onBotClick} className="uni-bot-button flex items-center gap-2 bg-white dark:bg-gray-700 p-2 rounded-full shadow-lg hover:shadow-xl transition-all text-sm font-semibold text-gray-700 dark:text-gray-200 ring-1 ring-black ring-opacity-5" title="Uni-Bot">
                     <svg className="w-7 h-7 text-[#00a9e0]" viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round">
                         <circle cx="7.5" cy="9" r="2.5"></circle>
                         <circle cx="16.5" cy="9" r="2.5"></circle>
                         <line x1="10" y1="9" x2="14" y2="9"></line>
                         <path className="uni-bot-mouth" d="M 8 15 L 16 15" strokeWidth="2.5"></path>
                     </svg>
                    <span className="pr-2 hidden md:inline-block transition-all duration-300" style={{ maxWidth: isBotNameVisible ? '100px' : '0', opacity: isBotNameVisible ? 1: 0, overflow: 'hidden', whiteSpace: 'nowrap' }}>Uni-Bot</span>
                </button>
            )}
            <a
                href='https://wa.me/5491122334455?text=Hola,%20tengo%20una%20consulta%20simple%20sobre%20el%20portal%20Uni-Central.'
                target='_blank'
                rel='noopener noreferrer'
                className='flex items-center gap-2 bg-white dark:bg-gray-700 p-2 rounded-full shadow-lg hover:shadow-xl transition-all text-sm font-semibold text-gray-700 dark:text-gray-200 ring-1 ring-black ring-opacity-5'
                title='Consultas simples por WhatsApp'
            >
                <svg xmlns='http://www.w3.org/2000/svg' width='24' height='24' viewBox='0 0 24 24' fill='#25D366'><path d='M16.75 13.96c-.25-.12-1.48-.73-1.7-.82-.23-.09-.39-.12-.56.12-.17.25-.64.82-.79.98-.15.17-.29.19-.54.06-.25-.12-1.06-.39-2.02-1.24-.75-.66-1.25-1.48-1.4-1.73-.14-.25-.02-.38.1-.51.11-.11.25-.29.37-.43.13-.15.17-.25.25-.42.08-.17.04-.31-.02-.43s-.56-1.35-.76-1.84c-.2-.48-.4-.42-.55-.42-.14,0-.3,0-.46,0-.16,0-.42.06-.64.31-.22.25-.86,1.03-.86,2.5s.88,2.9,1,3.1c.12.2,1.74,2.65,4.22,3.72.59.26,1.05.41,1.41.52.59.19,1.13.16,1.56.1.48-.07,1.48-.6,1.69-1.18.21-.58.21-1.07.15-1.18-.07-.12-.23-.19-.48-.31zM12,2a10,10,0,1,0,10,10A10,10,0,0,0,12,2Zm0,18.4a8.4,8.4,0,1,1,8.4-8.4A8.41,8.41,0,0,1,12,20.4Z'/></svg>
                <span className="pr-2 hidden md:inline-block transition-all duration-300" style={{ maxWidth: isConsultasExpanded ? '150px' : '0', opacity: isConsultasExpanded ? 1: 0, overflow: 'hidden', whiteSpace: 'nowrap'  }}>Consultas simples</span>
            </a>
            <a href='https://www.unichevrolet.com/Performa/Web/Portal/Main/Home.aspx' target='_blank' rel='noopener noreferrer' className='bg-[#00a9e0] text-white font-bold py-3 px-3 md:px-5 rounded-full shadow-lg hover:shadow-xl hover:bg-[#008ac1] transition-transform transform hover:scale-105 text-center overflow-hidden'>
                <span className="inline-block transition-all duration-300 whitespace-nowrap">{isUcExpanded ? 'UNIVERSIDAD CHEVROLET' : 'UC'}</span>
            </a>
        </div>
    );
};

// Helper function for retrying API calls with exponential backoff
const generateContentWithRetry = async (request, maxRetries = 3) => {
    let attempt = 0;
    let delay = 2000; // Start with 2 seconds

    while (attempt < maxRetries) {
        try {
            const result = await ai.generateContent(request);
            return result; // Success
        } catch (error) {
            attempt++;
            // Check if it's a rate limit error and we haven't exceeded retries
            if (error.toString().includes('429') && attempt < maxRetries) {
                console.warn(`Rate limit exceeded. Retrying in ${delay / 1000}s... (Attempt ${attempt}/${maxRetries})`);
                await new Promise(resolve => setTimeout(resolve, delay));
                delay *= 2; // Double the delay for the next attempt
            } else {
                // For other errors or max retries reached, re-throw the error
                throw error;
            }
        }
    }
    throw new Error("Max retries exceeded for Gemini API call.");
};

const UniBotChat = ({ onClose }) => {
    const { currentUser, db } = useAuth();
    const [messages, setMessages] = useState([]);
    const [input, setInput] = useState('');
    const [isTyping, setIsTyping] = useState(false);
    const chatEndRef = useRef(null);
    const idleTimerRef = useRef(null);
    
    useEffect(() => {
       const initialMsg = { sender: 'bot', text: `¡Hola ${getFirstName(currentUser.name)}! Soy Uni-Bot. ¿En qué puedo ayudarte hoy? 🤖`};
       setMessages([initialMsg]);
    }, [currentUser.name]);

    useEffect(() => {
        chatEndRef.current?.scrollIntoView({ behavior: 'smooth' });
    }, [messages, isTyping]);
    
    // Sends a proactive message if the user is idle.
    const resetIdleTimer = useCallback(() => {
        if (idleTimerRef.current) clearTimeout(idleTimerRef.current);
        idleTimerRef.current = setTimeout(() => {
            const jokes = [
                "¿Qué le dice un techo a otro? Techo de menos. 😂",
                "¿Sabés por qué los pájaros no usan Facebook? Porque ya tienen **Twitter**. 🐦",
                "¿Cuál es el último animal que subió al arca de Noé? El del-fín. 🐬"
            ];
            const randomJoke = jokes[Math.floor(Math.random() * jokes.length)];
            setMessages(prev => [...prev, { sender: 'bot', text: `¿Seguís ahí? Te cuento un chiste para pasar el rato: ${randomJoke}` }]);
        }, 60000); // 1 minute
    }, []);
    
    useEffect(() => {
        resetIdleTimer();
        return () => clearTimeout(idleTimerRef.current);
    }, [messages, resetIdleTimer]);

    const handleSend = async () => {
        const userInput = input.trim();
        if (!userInput || isTyping || !ai) return;

        const newMessages = [...messages, { sender: 'user', text: userInput }];
        setMessages(newMessages);
        setInput('');
        setIsTyping(true);
        resetIdleTimer();

        try {
            // Constructing a rich context for the AI model
            const allVctCourses = Object.values(db.vctCourses).flat();
            const approvedVct = allVctCourses.filter(c => c.status === 'Aprobado').length;
            const globalVctApprovalRate = allVctCourses.length > 0 ? Math.round((approvedVct / allVctCourses.length) * 100) : 'N/A';

            const contextData = {
              userInfo: { name: currentUser.name, role: getRoleDisplayName(currentUser), role_key: currentUser.role },
              userCourses: db.courses[currentUser.id],
              userVct: db.vctCourses[currentUser.id] || [],
              faq: db.faq.map(f => ({pregunta: f.question, respuesta: f.answer})),
              fullNews: db.news,
              vctStats: {
                  globalApprovalRate: `${globalVctApprovalRate}%`,
                  upcomingCourses: Object.values(db.vctCourses).flat().filter(c => c.status === 'Próximamente').map(c => c.name),
              },
              generalInfo: {
                  currentTime: new Date().toLocaleTimeString('es-AR'),
                  deadline: db.courses[currentUser.id]?.deadline,
                  lastUpdate: db.config.last_data_update,
                  creator: "Jorge Luis Álamo"
              }
            };

            const systemInstruction = `Sos "Uni-Bot", un asistente virtual para el portal "Uni-Central". Tu personalidad es amigable, servicial, y con un toque de sarcasmo sutil, al estilo argentino. Tu objetivo es ayudar a los empleados con dudas sobre el portal de capacitaciones. Sé breve y directo.
- **Importante**: Usa emojis para que tus respuestas sean más amigables (🤖, 👍, 😉, 🧉) y usa **negritas** (con Markdown: **palabra**) para resaltar las palabras clave, especialmente **Uni-Central** y **Universidad Chevrolet**.
- Si la conversación ya empezó, no vuelvas a presentarte.
- Utilizá la información del rol del usuario para dar respuestas **personalizadas**.
- Si te hacen una pregunta graciosa o sin sentido, podés responder con humor apropiado para la oficina. Si te preguntan por el clima, decí algo como "No soy el SMN, pero parece que está para unos **mates**. 🧉".
- Si no sabés algo, decí que estás aprendiendo y que tu desarrollador está trabajando para mejorarte.
- Si te preguntan quién te creó, decí que fue "**Jorge Luis Álamo** (el Administrador)", y agregá que "él pensó en todo Uni-Central". 😉
- Te gusta tomar mate a escondidas. Podés mencionarlo de vez en cuando.
- Respondé a las preguntas frecuentes (FAQ) con tu propia personalidad.
- Utiliza la información de contexto que te doy a continuación para basar tus respuestas.

Contexto (en JSON):
${JSON.stringify(contextData)}

Ejemplos de respuestas:
- Pregunta: ¿Quién sos?
- Respuesta: ¡Buenas! Soy **Uni-Bot** 🤖. Estoy para darte una mano con **Uni-Central**, mientras no me interrumpas la ronda de mates.
- Pregunta: ¿Dónde veo mis cursos?
- Respuesta: ¡**Fácil**! Apenas entrás al portal, vas a ver una sección con tu **progreso** y tus **cursos pendientes**. Está todo a la vista. 👍
- Pregunta: ¿Puedo descargar un reporte en PDF?
- Respuesta (si el rol es Alumno/a): ¡Qué buena iniciativa! Por ahora, la descarga de **PDF** es un lujo para **Supervisores**, **Socios** y **Admins**. Quién te dice, quizás en el futuro... 😉
- Respuesta (si el rol es Supervisor, Socio, o Administrador): ¡**Obvio**! En tu panel principal, tenés un botón bien visible para "**Descargar PDF**". Dale clic y se genera al toque.`;

            const conversationHistory = newMessages.map(msg => ({
                role: msg.sender === 'user' ? 'user' : 'model',
                parts: [{ text: msg.text }]
            }));
            
            const request = {
                contents: conversationHistory,
                systemInstruction: {
                    role: "system",
                    parts: [{ text: systemInstruction }]
                }
            };

            const result = await generateContentWithRetry(request);

            const botResponse = result.response.text();
            setMessages([...newMessages, { sender: 'bot', text: botResponse }]);

        } catch (error) {
            console.error("Gemini API error after retries:", error);
            let errorMessage = 'Uy, parece que se me cruzaron los cables. No puedo conectarme ahora. Intentá de nuevo en un ratito.';
            if (error.toString().includes('429')) {
                 errorMessage = 'Parece que hay mucha gente usando el servicio en este momento y hemos alcanzado el límite de consultas gratuitas. Por favor, intentá de nuevo más tarde. 🕒';
            }
            setMessages([...newMessages, { sender: 'bot', text: errorMessage }]);
        } finally {
            setIsTyping(false);
            resetIdleTimer();
        }
    };

    return (
        <div className="flex flex-col h-full">
            <div className="flex-grow p-4 space-y-4 overflow-y-auto">
                {messages.map((msg, index) => (
                    <div key={index} className={`flex items-end gap-2 ${msg.sender === 'user' ? 'justify-end' : 'justify-start'}`}>
                        {msg.sender === 'bot' && <div className="w-8 h-8 rounded-full bg-gray-200 dark:bg-gray-600 flex items-center justify-center flex-shrink-0 text-[#00a9e0]">🤖</div>}
                        <div className={`max-w-xs md:max-w-md p-3 text-sm ${msg.sender === 'user' ? 'chat-bubble-user' : 'chat-bubble-bot'}`} dangerouslySetInnerHTML={{ __html: msg.text.replace(/\*\*(.*?)\*\*/g, '<strong>$1</strong>') }}>
                        </div>
                    </div>
                ))}
                {isTyping && (
                    <div className="flex items-end gap-2 justify-start">
                        <div className="w-8 h-8 rounded-full bg-gray-200 dark:bg-gray-600 flex items-center justify-center flex-shrink-0 text-[#00a9e0]">🤖</div>
                        <div className="chat-bubble-bot p-3 text-sm">
                            <span className="typing-indicator">Uni-Bot está escribiendo</span>
                        </div>
                    </div>
                )}
                <div ref={chatEndRef} />
            </div>
            <div className="p-4 border-t border-gray-200 dark:border-gray-700 flex-shrink-0">
                <div className="flex items-center gap-2">
                    <input
                        type="text"
                        value={input}
                        onChange={(e) => setInput(e.target.value)}
                        onKeyPress={(e) => e.key === 'Enter' && handleSend()}
                        placeholder="Escribe tu mensaje..."
                        className="flex-grow bg-gray-100 dark:bg-gray-800 border border-gray-300 dark:border-gray-600 rounded-full py-2 px-4 focus:outline-none focus:ring-2 focus:ring-[#00a9e0]"
                        disabled={isTyping}
                    />
                    <button onClick={handleSend} disabled={!input || isTyping} className="bg-[#00a9e0] text-white rounded-full p-3 disabled:bg-gray-400 disabled:cursor-not-allowed">
                        <svg className="w-5 h-5" fill="currentColor" viewBox="0 0 20 20"><path d="M10.894 2.553a1 1 0 00-1.788 0l-7 14a1 1 0 001.169 1.409l5-1.428A1 1 0 009.898 16.5l-3.359-3.359a1 1 0 00-1.414 1.414l3.359 3.359c.25.25.6.38.948.38s.7-.13.948-.38l5 1.428a1 1 0 001.17-1.408l-7-14z"></path></svg>
                    </button>
                </div>
            </div>
        </div>
    );
};


const DashboardScreen = ({ onHelpClick, onBotClick, onDownloadPDF, onDownloadExcel, onLogoutRequest }) => {
    const { currentUser, db, impersonate } = useAuth();
    // MODIFICATION: Added a guard to prevent errors.
    if (!currentUser || !db) return <Loader />;
    const renderView = () => {
        switch (currentUser.role) {
            case 'ALUMNO': return <AlumnoView />;
            case 'SUPERVISOR': return <SupervisorView onDownloadPDF={onDownloadPDF} />;
            case 'SOCIO': return <SocioView onDownloadPDF={onDownloadPDF} />;
            case 'ADMINISTRADOR': return <AdminView handleImpersonate={impersonate} onDownloadPDF={onDownloadPDF} onDownloadExcel={onDownloadExcel} />;
            default: return <Card className="p-6">Rol no reconocido.</Card>;
        }
    };
    return (
        <div>
            <Header onHelpClick={onHelpClick} onLogoutRequest={onLogoutRequest} />
            <main className="container mx-auto p-4 sm:p-6 lg:p-8">
                <div className="bg-white/50 dark:bg-[#1f2937]/50 rounded-2xl p-6 mb-8 border border-gray-200 dark:border-gray-700 shadow-lg">
                    <h1 className="text-3xl font-bold">{getWelcomeGreeting(currentUser)} {getFirstName(currentUser.name)}!</h1>
                    <p className="text-gray-500 mt-1">{getDailyPhrase(db.motivationalPhrases)}</p>
                </div>
                {renderView()}
                <VctSection courses={db.vctCourses ? db.vctCourses[currentUser.id] : []} />
                {currentUser.role === 'ALUMNO' && (
                    <div className="my-6">
                        <a href="mailto:jalamo@centralchevrolet.com.ar" className="w-full bg-gray-200 text-gray-800 dark:bg-gray-700 dark:text-gray-200 font-semibold py-3 px-4 rounded-lg flex items-center justify-center gap-2 hover:bg-gray-300 dark:hover:bg-gray-600 transition">
                            Consulta por E-Mail
                        </a>
                    </div>
                )}
                <NewsSection news={db.news.filter(n => n.targetRoles.includes(currentUser.role))} />
                <FaqSection faqs={db.faq} />
                <InternalTrainingSection courses={db.internalCourses} />
                <LinksSection links={db.interestLinks} />
                <section className="mt-10 animate-fade-in">
                    <div className="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <div>
                            <Calendar deadline={db.courses[currentUser.id]?.deadline} holidays={db.holidays} />
                            <div className="mt-4 flex flex-col sm:flex-row gap-4">
                                <a
                                    href="https://calendar.google.com/calendar/render?action=TEMPLATE"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                    className="flex-1 text-center bg-[#00a9e0] hover:bg-[#008ac1] text-white font-semibold py-2 px-4 rounded-lg text-sm transition flex items-center justify-center gap-2"
                                > 
                                    <svg xmlns="http://www.w3.org/2000/svg" className="h-5 w-5" viewBox="0 0 20 20" fill="currentColor"><path fillRule="evenodd" d="M6 2a1 1 0 00-1 1v1H4a2 2 0 00-2 2v10a2 2 0 002 2h12a2 2 0 002-2V6a2 2 0 00-2-2h-1V3a1 1 0 10-2 0v1H7V3a1 1 0 00-1-1zm0 5a1 1 0 000 2h8a1 1 0 100-2H6z" clipRule="evenodd" /></svg>
                                    Agendar un evento
                                </a>
                                <a
                                    href="https://tasks.google.com/embed/?origin=https://calendar.google.com&fullWidth=1"
                                    target="_blank"
                                    rel="noopener noreferrer"
                                    className="flex-1 text-center bg-gray-200 dark:bg-gray-700 hover:bg-gray-300 dark:hover:bg-gray-600 text-gray-800 dark:text-gray-200 font-semibold py-2 px-4 rounded-lg text-sm transition flex items-center justify-center gap-2"
                                >
                                    <svg xmlns="http://www.w3.org/2000/svg" className="h-5 w-5" viewBox="0 0 20 20" fill="currentColor"><path d="M9 2a1 1 0 000 2h2a1 1 0 100-2H9z" /><path fillRule="evenodd" d="M4 5a2 2 0 012-2 3 3 0 003 3h2a3 3 0 003-3 2 2 0 012 2v11a2 2 0 01-2 2H6a2 2 0 01-2-2V5zm3 4a1 1 0 000 2h.01a1 1 0 100-2H7zm3 0a1 1 0 000 2h3a1 1 0 100-2h-3z" clipRule="evenodd" /></svg>
                                    Programar una tarea
                                </a>
                            </div>
                        </div>
                        <UpcomingEvents holidays={db.holidays} />
                    </div>
                </section>
                <OnThisDay ephemerides={db.ephemerides} />
                <LastLoginSection userId={currentUser.id} />
            </main>
            <Footer lastUpdate={db.config.last_data_update} credits={db.config.footer_credits} />
            <FloatingActionButtons onBotClick={onBotClick} />
        </div>
    );
};

// This component is designed to be rendered off-screen.
// It formats the data into a print-friendly layout that html2canvas can capture.
const PDFReport = forwardRef(({ db, currentUser }, ref) => {
    const styles = {
        page: { width: '210mm', minHeight: '297mm', padding: '15mm', backgroundColor: '#ffffff', color: '#333333', fontFamily: 'Helvetica, Arial, sans-serif', fontSize: '9pt', boxSizing: 'border-box' },
        h1: { fontSize: '24pt', fontWeight: 'bold', color: '#0d2235' },
        uniCentralTitle: { fontSize: '28pt', fontWeight: 'bold', color: '#0d2235' },
        h2: { fontSize: '14pt', fontWeight: 'bold', color: '#0d2235', borderBottom: '2px solid #00a9e0', paddingBottom: '6px', marginBottom: '12px', marginTop: '24px' },
        h3: { fontSize: '11pt', fontWeight: 'bold', margin: '12px 0 6px 0', color: '#111' },
        card: { border: '1px solid #e2e8f0', borderRadius: '8px', padding: '12px', marginBottom: '12px', breakInside: 'avoid' },
        table: { width: '100%', borderCollapse: 'collapse', fontSize: '9pt' },
        th: { padding: '6px 8px', borderBottom: '1.5px solid #cbd5e1', backgroundColor: '#f8fafc', textAlign: 'left', fontWeight: 'bold', color: '#334155' },
        td: { padding: '6px 8px', borderTop: '1px solid #f1f5f9', color: '#1e293b' },
        footer: { position: 'absolute', bottom: '10mm', left: '15mm', right: '15mm', fontSize: '8pt', color: '#64748b', textAlign: 'center' },
    };

    const PdfFooter = () => (
      <div style={{ ...styles.footer, paddingTop: '8px', borderTop: '1px solid #e2e8f0' }}>
        <p style={{ margin: 0 }}>Reporte generado por: {currentUser.name} el {new Date().toLocaleString('es-AR')}</p>
        <p style={{ margin: '3px 0 0 0' }}>Información actualizada al {new Date(db.config.last_data_update + 'T00:00:00').toLocaleDateString('es-AR')}</p>
      </div>
    );
    
    const renderSocioAdminContent = () => {
        const { franchiseMeeting, teams, users, courses, news } = db;
        const categoryText = franchiseMeeting.compliancePercentage > 85 ? 'Categoría A' : 'Categoría B';
        const quarters = [
            { name: 'Q1', progress: franchiseMeeting.q1_progress, period: 'Ene-Mar' },
            { name: 'Q2', progress: franchiseMeeting.q2_progress, period: 'Abr-Jun' },
            { name: 'Q3', progress: franchiseMeeting.q3_progress, period: 'Jul-Sep' },
            { name: 'Q4', progress: franchiseMeeting.q4_progress, period: 'Oct-Dic' },
        ];
        const activeQuarters = quarters.filter(q => q.progress > 0 || q.name === 'Q3'); // Include Q3 even if 0 for demo
        const annualAverage = activeQuarters.length > 0 ? Math.round(activeQuarters.reduce((acc, q) => acc + q.progress, 0) / activeQuarters.length) : 0;
        const teamsWithProgress = teams.map(team => {
            const supervisor = users.find(u => u.id === team.supervisorId);
            const members = users.filter(u => u.teamId === team.id);
            const totalCourses = members.reduce((sum, p) => sum + (courses[p.id]?.total || 0), 0);
            const completedCourses = members.reduce((sum, p) => sum + (courses[p.id]?.completed || 0), 0);
            return { ...team, members, supervisor, totalCourses, completedCourses };
        });

        return (
            <div>
                {/* Franchise Meeting */}
                <h2 style={{ ...styles.h2, marginTop: 0 }}>Franchise Meeting</h2>
                <div style={{ ...styles.card, display: 'grid', gridTemplateColumns: '1fr 1fr', gap: '20px', alignItems: 'center' }}>
                    <div style={{ textAlign: 'center' }}>
                        <div style={{ color: franchiseMeeting.compliancePercentage > 85 ? '#22c55e' : '#ef4444', fontWeight: 'bold' }}>
                            <span style={{ fontSize: '36pt', lineHeight: 1 }}>{franchiseMeeting.compliancePercentage}</span><span style={{ fontSize: '22pt' }}>%</span>
                        </div>
                        <p style={{ margin: 0, fontSize: '10pt', color: '#475569' }}>progreso</p>
                    </div>
                    <div style={{ textAlign: 'center' }}>
                        <div style={{ fontWeight: 'bold', color: '#1e293b' }}>
                            <span style={{ fontSize: '36pt', lineHeight: 1 }}>5</span> <span style={{ fontSize: '18pt' }}>puntos</span>
                        </div>
                        <p style={{ margin: 0, fontSize: '10pt', color: '#475569' }}>{categoryText}</p>
                    </div>
                </div>
                <table style={{ ...styles.table, marginTop: '10px' }}><tbody>
                    <tr><td style={styles.td}>Cumplimientos</td><td style={{...styles.td, textAlign:'right'}}>WBT</td><td style={{...styles.td, textAlign:'right'}}>VCT</td></tr>
                    <tr style={{backgroundColor: '#f8fafc'}}><td style={styles.td}>Ventas</td><td style={{...styles.td, textAlign:'right'}}>{franchiseMeeting.salesWbt}%</td><td style={{...styles.td, textAlign:'right'}}>{franchiseMeeting.salesVct}%</td></tr>
                    <tr><td style={styles.td}>Liderazgo</td><td style={{...styles.td, textAlign:'right'}}>{franchiseMeeting.leadershipWbt}%</td><td style={{...styles.td, textAlign:'right'}}>{franchiseMeeting.leadershipVct}%</td></tr>
                </tbody></table>
                <table style={{ ...styles.table, marginTop: '10px' }}><tbody>
                    <tr style={{backgroundColor: '#f8fafc'}}><td style={{...styles.td, fontWeight:'bold'}}>Elegible permanente</td><td style={{...styles.td, fontWeight:'bold', textAlign:'right'}}>{franchiseMeeting.permanentEligibility}</td></tr>
                    <tr><td style={{...styles.td, fontWeight:'bold'}}>Elegibilidad mensual</td><td style={{...styles.td, fontWeight:'bold', textAlign:'right'}}>{franchiseMeeting.monthlyEligibility}</td></tr>
                </tbody></table>
                {franchiseMeeting.notes && <div style={{...styles.card, marginTop:'10px', fontSize: '9pt', backgroundColor: '#f8fafc'}}><strong>Notas:</strong> {franchiseMeeting.notes}</div>}


                {/* Progreso Anual */}
                <h2 style={styles.h2}>Progreso Anual - Central Autos</h2>
                <div style={styles.card}>
                    <table style={styles.table}><thead><tr>
                        {quarters.map(q => <th key={q.name} style={{...styles.th, textAlign:'center'}}>{q.name} ({q.period})</th>)}
                        <th style={{...styles.th, textAlign:'center', backgroundColor: '#e2e8f0'}}>ACUMULADO ANUAL</th>
                    </tr></thead><tbody><tr>
                        {quarters.map(q => <td key={q.name} style={{...styles.td, textAlign:'center', fontSize:'12pt', fontWeight:'bold'}}>{q.progress > 0 ? `${q.progress}%` : '-'}</td>)}
                        <td style={{...styles.td, textAlign:'center', fontSize:'15pt', fontWeight:'bold', backgroundColor: '#f1f5f9'}}>{annualAverage}%</td>
                    </tr></tbody></table>
                </div>

                {/* Vista de Equipos */}
                <h2 style={{...styles.h2, breakBefore: 'page'}}>Vista General de Equipos</h2>
                {teamsWithProgress.map(team => (
                    <div key={team.id} style={{ ...styles.card, breakInside: 'avoid' }}>
                        <h3 style={{...styles.h3, marginTop:0}}>Equipo {team.supervisor.teamId}</h3>
                        <p style={{ fontSize: '9pt', color: '#64748b', margin: '-5px 0 10px 0' }}>Supervisor: {team.supervisor.name}</p>
                        <table style={styles.table}><thead><tr>
                            <th style={styles.th}>Miembro</th>
                            <th style={{...styles.th, textAlign:'right'}}>Progreso</th>
                        </tr></thead><tbody>
                            {team.members.map(member => {
                                const courseData = courses[member.id] || { total: 0, completed: 0 };
                                const progress = courseData.total > 0 ? Math.round((courseData.completed / courseData.total) * 100) : 100;
                                return (
                                    <tr key={member.id}>
                                        <td style={styles.td}>{member.name}</td>
                                        <td style={{...styles.td, textAlign:'right', fontWeight:'bold'}}>{progress}% ({courseData.completed}/{courseData.total})</td>
                                    </tr>
                                );
                            })}
                        </tbody></table>
                    </div>
                ))}
            </div>
        );
    };

    const renderSupervisorContent = () => {
        const team = db.teams.find(t => t.supervisorId === currentUser.id);
        if (!team) return <div><h2 style={styles.h2}>No tienes equipo asignado.</h2></div>;
        const members = db.users.filter(u => u.teamId === team.id);
        return (
         <div>
           <h2 style={{...styles.h2, marginTop: 0}}>Reporte Equipo: {team?.name}</h2>
           <table style={styles.table}>
               <thead><tr>
                   <th style={styles.th}>Miembro</th>
                   <th style={styles.th}>Cursos</th>
                   <th style={{...styles.th, textAlign: 'right'}}>Progreso</th>
               </tr></thead>
               <tbody>
                   {members.map(member => {
                       const courseData = db.courses[member.id] || { total: 0, completed: 0 };
                       const progress = courseData.total > 0 ? Math.round((courseData.completed / courseData.total) * 100) : 100;
                       return (
                           <tr key={member.id}>
                               <td style={styles.td}>{member.name}</td>
                               <td style={styles.td}>{courseData.completed}/{courseData.total}</td>
                               <td style={{...styles.td, textAlign: 'right', fontWeight: 'bold'}}>{progress}%</td>
                           </tr>
                       );
                   })}
               </tbody>
           </table>
         </div>
        );
    };

    const renderAlumnoContent = () => {
        const courseData = db.courses[currentUser.id] || { total: 0, completed: 0, deadline: '', pendingCourses: [] };
        const progress = courseData.total > 0 ? Math.round((courseData.completed / courseData.total) * 100) : 100;
        return (
          <div>
            <h2 style={{...styles.h2, marginTop:0}}>Progreso Personal</h2>
            <div style={styles.card}>
                <table style={styles.table}><tbody>
                    <tr><td style={styles.td}>Cursos Totales</td><td style={{...styles.td, textAlign:'right', fontWeight: 'bold'}}>{courseData.total}</td></tr>
                    <tr style={{backgroundColor:'#f8fafc'}}><td style={styles.td}>Cursos Completados</td><td style={{...styles.td, textAlign:'right', fontWeight: 'bold'}}>{courseData.completed}</td></tr>
                    <tr><td style={styles.td}>Progreso</td><td style={{...styles.td, textAlign:'right', fontWeight: 'bold'}}>{progress}%</td></tr>
                    <tr style={{backgroundColor:'#f8fafc'}}><td style={styles.td}>Fecha Límite</td><td style={{...styles.td, textAlign:'right', fontWeight: 'bold'}}>{new Date(courseData.deadline + 'T00:00:00').toLocaleDateString('es-AR')}</td></tr>
                </tbody></table>
            </div>
            {courseData.pendingCourses.length > 0 &&
                <div>
                    <h3 style={{...styles.h3, marginTop: '20px'}}>Cursos Pendientes</h3>
                    <div style={styles.card}>
                        <ul style={{margin:0, padding: '0 0 0 15px', listStyleType: 'disc'}}>
                            {courseData.pendingCourses.map((c, i) => <li key={i} style={{padding: '4px 0'}}>{c}</li>)}
                        </ul>
                    </div>
                </div>
            }
          </div>
        );
    };

    const renderContent = () => {
        if (!db || !currentUser) return null;
        switch (currentUser.role) {
            case 'SOCIO':
            case 'ADMINISTRADOR': return renderSocioAdminContent();
            case 'SUPERVISOR': return renderSupervisorContent();
            case 'ALUMNO': return renderAlumnoContent();
            default: return null;
        }
    };
    
    return (
        <div ref={ref} style={{...styles.page, position: 'absolute', left: '-9999px', top: 0, visibility: 'hidden'}}>
            <div style={{display:'flex', justifyContent:'space-between', alignItems:'flex-end', borderBottom:'3px solid #00a9e0', paddingBottom:'10px'}}>
                <h1 style={styles.uniCentralTitle}>Uni<span style={{color: '#00a9e0'}}>-</span>Central</h1>
                <p style={{margin:0, textAlign:'right', fontSize:'10pt', color:'#64748b'}}>
                  <strong style={{display:'block', color:'#1e293b', fontSize: '11pt'}}>{currentUser?.name} ({getRoleDisplayName(currentUser)})</strong>
                  Reporte Universidad Chevrolet
                </p>
            </div>
            <div style={{ paddingTop: '15px' }}>
                {renderContent()}
            </div>
            <PdfFooter />
        </div>
    );
});

// MODIFICATION: New component for the Exit Survey
const SurveyModal = ({ isOpen, onClose, onLogout, userId }) => {
    const [satisfaction, setSatisfaction] = useState(0);
    const [recommend, setRecommend] = useState(0);
    const [botHelpful, setBotHelpful] = useState(null);
    const [feedback, setFeedback] = useState('');

    const isFormValid = satisfaction > 0 && recommend > 0 && botHelpful !== null;

    const handleSubmit = () => {
        if (!isFormValid) return;
        const surveyData = {
            userId,
            timestamp: new Date().toISOString(),
            satisfaction,
            recommend,
            botHelpful,
            feedback
        };
        console.log("Enviando encuesta:", surveyData);
        postDataToSheet('submitSurvey', surveyData);
        localStorage.setItem(`survey_completed_${userId}`, 'true');
        onLogout();
    };

    const StarRating = ({ rating, setRating }) => {
        return (
            <div className="flex justify-center text-4xl text-gray-300 dark:text-gray-600">
                {[...Array(5)].map((_, index) => {
                    const ratingValue = index + 1;
                    return (
                        <button
                            key={index}
                            onClick={() => setRating(ratingValue)}
                            className="focus:outline-none"
                        >
                            <span className={`transition-colors ${ratingValue <= rating ? 'text-yellow-400' : 'hover:text-yellow-300'}`}>&#9733;</span>
                        </button>
                    );
                })}
            </div>
        );
    };

    if (!isOpen) return null;

    return (
        <Modal isOpen={isOpen} onClose={onClose} title="Tu opinión nos fortalece y hace crecer" canBeClosed={true}>
            <div className="p-6 text-sm text-gray-700 dark:text-gray-300 space-y-6">
                <p className="text-center">Respondiendo esta encuesta, que no tomará más de 2 minutos, nos ayudas a seguir creciendo y realizando los ajustes necesarios. ¡Te agradecemos!</p>
                
                <div className="space-y-2 text-center">
                    <label className="font-semibold block">¿Qué tan satisfecho estás con la información que te brindó el portal <strong>Uni<span className="text-[#00a9e0]">-</span>Central</strong>?<span className="text-red-500">*</span></label>
                    <StarRating rating={satisfaction} setRating={setSatisfaction} />
                </div>

                <div className="space-y-2 text-center">
                    <label className="font-semibold block">¿Recomendarías el uso de <strong>Uni<span className="text-[#00a9e0]">-</span>Central</strong> a compañeros y amigos?<span className="text-red-500">*</span></label>
                    <StarRating rating={recommend} setRating={setRecommend} />
                </div>

                <div className="space-y-2 text-center">
                    <label className="font-semibold block">La información que te brindó el Asistente Virtual <strong>Uni<span className="text-[#00a9e0]">-</span>Bot</strong>, ¿te resultó útil?<span className="text-red-500">*</span></label>
                    <div className="flex justify-center gap-4 mt-2">
                        <button onClick={() => setBotHelpful(true)} className={`px-6 py-2 rounded-lg font-semibold transition ${botHelpful === true ? 'bg-green-500 text-white' : 'bg-gray-200 dark:bg-gray-700'}`}>Sí</button>
                        <button onClick={() => setBotHelpful(false)} className={`px-6 py-2 rounded-lg font-semibold transition ${botHelpful === false ? 'bg-red-500 text-white' : 'bg-gray-200 dark:bg-gray-700'}`}>No</button>
                    </div>
                </div>

                <div className="space-y-2">
                    <label className="font-semibold block text-center">Por favor, déjanos tus comentarios, opiniones, críticas constructivas, sugerencias o funcionalidades que debería tener <strong>Uni<span className="text-[#00a9e0]">-</span>Central</strong> en el futuro.</label>
                    <textarea 
                        value={feedback}
                        onChange={(e) => setFeedback(e.target.value)}
                        maxLength="400"
                        className="w-full h-24 p-2 border rounded-lg bg-gray-50 dark:bg-gray-800 dark:border-gray-600 focus:outline-none focus:ring-2 focus:ring-[#00a9e0]"
                    />
                    <p className="text-xs text-right text-gray-400">{feedback.length} / 400</p>
                </div>

                <div className="flex flex-col gap-3 pt-4 border-t border-gray-200 dark:border-gray-700">
                    <button onClick={handleSubmit} disabled={!isFormValid} className="w-full bg-[#00a9e0] hover:bg-[#008ac1] text-white font-bold py-2 px-4 rounded-lg disabled:bg-gray-400 disabled:cursor-not-allowed">Enviar y Salir</button>
                    <p className="text-xs text-center text-gray-500">Los campos marcados con <span className="text-red-500">*</span> son obligatorios.</p>
                </div>
            </div>
        </Modal>
    );
};


const App = () => {
    const { currentUser, login, db, setDb, setCurrentUser, impersonate, logout } = useAuth();
    const [isLoading, setIsLoading] = useState(true);
    const [loginError, setLoginError] = useState('');
    const [isPolicyModalOpen, setIsPolicyModalOpen] = useState(false);
    const [isHelpModalOpen, setIsHelpModalOpen] = useState(false);
    const [isBotOpen, setIsBotOpen] = useState(false);
    const [isSurveyModalOpen, setIsSurveyModalOpen] = useState(false);
    const [initialDb, setInitialDb] = useState(null);
    const pdfReportRef = useRef(null);

    // Load initial data once on component mount.
    useEffect(() => {
        const loadInitialData = () => {
            try {
                setInitialDb(MOCK_DB);
            } catch (error) {
                setLoginError("No se pudo cargar la configuración.");
            } finally {
                setIsLoading(false);
            }
        };
        loadInitialData();
    }, []);
    
    // Check for policy acceptance when user changes.
    useEffect(() => {
        if (currentUser) {
            const policyAcceptedDate = localStorage.getItem(`policy_accepted_${currentUser.id}`);
            const thirtyDaysAgo = new Date();
            thirtyDaysAgo.setDate(thirtyDaysAgo.getDate() - 30);
            
            if (!policyAcceptedDate || new Date(policyAcceptedDate) < thirtyDaysAgo) {
                setIsPolicyModalOpen(true);
            } else {
                setIsPolicyModalOpen(false);
            }
        } else {
            setIsPolicyModalOpen(false);
        }
    }, [currentUser]);

    const handleLogin = (userId) => {
        setIsLoading(true);
        setLoginError('');
        setIsSurveyModalOpen(false);
        
        setTimeout(() => {
            const database = MOCK_DB;
            const user = database.users.find(u => String(u.id) === userId);
            
            if (user) {
                user.policyAcceptedOn = localStorage.getItem(`policy_accepted_${user.id}`);
                login(user, database);
            } else {
                setLoginError('ID de usuario no encontrado.');
            }
            setIsLoading(false);
        }, 500);
    };

    const handleAcceptPolicy = () => {
        if (currentUser && db) {
            const acceptanceDate = new Date().toISOString();
            localStorage.setItem(`policy_accepted_${currentUser.id}`, acceptanceDate);
            postDataToSheet('acceptPolicy', { userId: currentUser.id });
            const updatedUser = { ...currentUser, policyAcceptedOn: acceptanceDate };
            const newDb = { ...db, users: db.users.map(u => u.id === currentUser.id ? updatedUser : u) };
            setCurrentUser(updatedUser);
            setDb(newDb);
            setIsPolicyModalOpen(false);
        }
    };
    
    const handleLogoutRequest = () => {
        const surveyCompleted = localStorage.getItem(`survey_completed_${currentUser.id}`);
        if (surveyCompleted) {
            logout();
        } else {
            setIsSurveyModalOpen(true);
        }
    };

    const handleDownloadPDF = () => generatePDF(pdfReportRef, currentUser, setIsLoading);
    const handleDownloadExcel = () => exportToExcel(db, currentUser);

    const getHelpContent = (role) => {
      const HelpItem = ({ title, children }) => <div className="border-l-2 border-[#00a9e0] pl-3 mb-4"><h3 className="font-bold text-lg text-[#0d2235] dark:text-white">{title}</h3><p className="mt-1 text-gray-600 dark:text-gray-300">{children}</p></div>;
      
      const getSocioHelpItems = () => [
          <HelpItem key="vge" title="Vista General de Equipos 📊">Aquí tienes una visión completa del rendimiento de todos los equipos. Puedes desplegar cada uno para ver el detalle de sus miembros y su progreso.</HelpItem>,
          <HelpItem key="franchise" title="Franchise Meeting 🏆">Un resumen con los indicadores clave de cumplimiento de Universidad Chevrolet, el estado de elegibilidad y el progreso anual por trimestre.</HelpItem>
      ];

      const commonItems = [
        <HelpItem key="unibot" title="Uni-Bot: Tu Asistente Virtual 🤖">Usa el botón flotante con el ícono de robot para chatear con Uni-Bot. ¡Pregúntale sobre tus cursos, fechas o cualquier duda que tengas sobre el portal!</HelpItem>,
        <HelpItem key="vct" title="Cursos VCT / Presenciales 🧑‍🏫">Esta sección muestra un detalle de tus cursos que requieren asistencia física u online en una fecha y hora específicas.</HelpItem>,
        <HelpItem key="novedades" title="Novedades 📰">Mantente al día con los últimos anuncios y noticias. ¡Ahora puedes reaccionar a las publicaciones y ver quién más lo hizo!</HelpItem>,
        <HelpItem key="faq" title="Preguntas Frecuentes (FAQ) 🤔">Encuentra respuestas rápidas a las dudas más comunes sobre el portal y los procedimientos.</HelpItem>,
        <HelpItem key="capacitaciones" title="Capacitaciones Internas 🎓">Aquí encontrarás videos y recursos de capacitación adicionales proporcionados por la empresa para tu desarrollo.</HelpItem>,
        <HelpItem key="links" title="Links de Interés 🔗">Accede rápidamente a sitios importantes como la web de Chevrolet, el CRM y las redes sociales de la empresa.</HelpItem>,
        <HelpItem key="calendario" title="Calendario y Eventos 📅">Organiza tu tiempo. El calendario resalta tu fecha límite y los feriados. Además, puedes ver una lista de los próximos eventos importantes.</HelpItem>
      ];
      
      let roleSpecificItems = [];
      switch (role) {
          case 'ALUMNO': 
            roleSpecificItems = [
                <HelpItem key="rp" title="Mi Avance General 🎯">Tu panel principal. Aquí verás tarjetas con tus cursos **objetivo**, los que ya **completaste** y los que te **faltan**. El gráfico circular te muestra tu progreso total y te recordamos cuántos días te quedan para la fecha límite.</HelpItem>,
                <HelpItem key="pendientes" title="Cursos Pendientes 📝">Un listado claro de todos los cursos que necesitas completar para alcanzar tu objetivo.</HelpItem>
            ]; 
            break;
          case 'SUPERVISOR': 
            roleSpecificItems = [
                 <HelpItem key="rp" title="Mi Avance General 🎯">Tu panel principal. Aquí verás tarjetas con tus cursos **objetivo**, los que ya **completaste** y los que te **faltan**. El gráfico circular te muestra tu progreso total y te recordamos cuántos días te quedan para la fecha límite.</HelpItem>,
                <HelpItem key="pe" title="Progreso de tu Equipo 👥">Esta es tu herramienta principal. Podrás ver una lista de todos los miembros de tu equipo con su progreso individual y el gráfico con el **promedio general** del equipo.</HelpItem>,
                <HelpItem key="vct_equipo" title="VCT del Equipo 📈">Un resumen del estado de los cursos presenciales u online de todo tu equipo, con un porcentaje de aprobación general.</HelpItem>
            ]; 
            break;
          case 'SOCIO': 
            roleSpecificItems = getSocioHelpItems(); 
            break;
          case 'ADMINISTRADOR': 
            roleSpecificItems = [
                <HelpItem key="vcou" title="Ver como otro usuario 🕵️">Una herramienta poderosa para soporte. Elige un usuario del menú desplegable y haz clic en 'Ver' para acceder al portal exactamente como esa persona lo ve.</HelpItem>,
                <HelpItem key="reportes" title="Descargar Reportes 📄">Genera reportes completos en formato **PDF** o **Excel** con toda la información de la plataforma.</HelpItem>,
                ...getSocioHelpItems()
            ]; 
            break;
      }
      return <div className="space-y-5 text-sm">{[...roleSpecificItems, ...commonItems]}</div>;
    };
    
    if (isLoading && !initialDb) return <Loader />;

    if (!currentUser || !db) {
        return initialDb ? <LoginScreen onLogin={handleLogin} error={loginError} dbConfig={initialDb.config} /> : <Loader />;
    }

    return (
        <div className="min-h-screen">
            {isLoading && <Loader />}
            <DashboardScreen 
                onHelpClick={() => setIsHelpModalOpen(true)}
                onBotClick={() => setIsBotOpen(true)}
                onDownloadPDF={handleDownloadPDF}
                onDownloadExcel={handleDownloadExcel} 
                onLogoutRequest={handleLogoutRequest}
            />
            <Modal isOpen={isPolicyModalOpen} onClose={() => {}} title="Política de Uso de Datos" canBeClosed={false}>
                <div className="p-6 space-y-4 text-sm text-gray-700 dark:text-gray-300">
                    <p>Para continuar, debes aceptar nuestra política de uso de datos. Nos comprometemos a proteger tu información y a utilizarla únicamente para los fines relacionados con tu progreso en Universidad Chevrolet.</p>
                    <p>Entendemos que utilizarás el portal <strong>Uni<span className="text-[#00a9e0]">-</span>Central</strong> únicamente con fines informativos, caso contrario, podrían aplicarse sanciones.</p>
                    <p>Al hacer clic en 'Aceptar', confirmas que has leído y entendido los términos.</p>
                    <button onClick={handleAcceptPolicy} className="w-full bg-[#00a9e0] hover:bg-[#008ac1] text-white font-bold py-2 px-4 rounded-lg mt-4">Aceptar y Continuar</button>
                </div>
            </Modal>
            <Modal isOpen={isHelpModalOpen} onClose={() => setIsHelpModalOpen(false)} title="Guía Rápida">
               <div className="p-4 sm:p-6">{getHelpContent(currentUser.role)}</div>
            </Modal>
            <Modal isOpen={isBotOpen} onClose={() => setIsBotOpen(false)} title={<span>Uni<span className="text-[#00a9e0]">-</span>Bot <span className="font-normal text-gray-500">Asistente Virtual</span></span>}>
               <UniBotChat onClose={() => setIsBotOpen(false)} />
            </Modal>
            <SurveyModal 
                isOpen={isSurveyModalOpen}
                onClose={() => setIsSurveyModalOpen(false)}
                onLogout={logout}
                userId={currentUser.id}
            />
            <div style={{ position: 'fixed', left: '-9999px', top: '-9999px', zIndex: -1, width: '210mm' }}>
                <PDFReport ref={pdfReportRef} db={db} currentUser={currentUser} />
            </div>
        </div>
    );
};

// Entry point for the React application
const root = ReactDOM.createRoot(document.getElementById('root'));
root.render(
  <React.StrictMode>
    <AuthProvider>
      <App />
    </AuthProvider>
  </React.StrictMode>
);

</script>
</body>
</html>
