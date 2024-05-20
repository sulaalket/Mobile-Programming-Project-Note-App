# Mobile-Programming-Project-Note-App
Note Mobile Application Using Android Studio and Java Language, XML Layouts, Google Firebase.


/*
 * Summary of the Note App Project
 * 
 * Project Overview:
 * This project is a note-taking app developed for Android. It allows users to create,
 * view, edit, and delete notes. The app uses Firebase for authentication and Firestore 
 * for storing notes.
 * 
 * Key Functionalities:
 * 1. User Authentication: Users can sign in to the app using Firebase Authentication.
 * 2. Create Notes: Users can create new notes with a title and content.
 * 3. View Notes: All notes are displayed in a grid layout. Users can click on a note 
 *    to view its details.
 * 4. Edit Notes: Users can edit the title and content of an existing note.
 * 5. Delete Notes: Users can delete notes they no longer need.
 * 
 * What I Learned from This Project:
 * 1. Android UI Design:
 *    - Using XML to design the user interface.
 *    - Employing RelativeLayout, LinearLayout, and CardView for layout design.
 *    - Adding custom styles and themes.
 * 
 * 2. RecyclerView:
 *    - Implementing RecyclerView to display a list of notes.
 *    - Using FirestoreRecyclerAdapter to bind Firestore data to the RecyclerView.
 * 
 * 3. Firebase Integration:
 *    - Setting up Firebase in an Android project.
 *    - Using Firebase Authentication for user sign-in.
 *    - Using Firestore for storing and retrieving notes.
 * 
 * 4. Intents and Data Passing:
 *    - Using Intent to navigate between activities and pass data.
 *    - Handling Intent data in different activities.
 * 
 * 5. Material Design Components:
 *    - Using FloatingActionButton for add and save actions.
 *    - Using Toolbar for a consistent app bar.
 * 
 * File Descriptions and Code Explanation:
 * 
 * notedetails.java:
 * - This file displays the details of a selected note.
 * - It initializes UI components like TextView for title and content, and a FloatingActionButton 
 *   for editing the note.
 * - It sets up a toolbar and retrieves note details from the intent.
 * - It provides an option to navigate to the editnoteactivity for editing the note.
 * 
 * notesActivity.java:
 * - This file displays a list of all notes using RecyclerView and FirestoreRecyclerAdapter.
 * - It initializes UI components like RecyclerView and FloatingActionButton.
 * - It sets up a StaggeredGridLayoutManager for the RecyclerView to display notes in a grid layout.
 * - It provides functionality for creating a new note and handling user interactions like 
 *   viewing, editing, and deleting notes.
 * 
 * References:
 * - Tech Projects YouTube Channel: https://www.youtube.com/@TechProjects
 * - Mobile Programming Lecture's Slides
 * - Stack Overflow: https://stackoverflow.com
 */
