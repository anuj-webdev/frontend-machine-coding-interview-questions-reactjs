# Frontend Machine Coding Interview Questions in React JS
Here are the 30 Most Asked [Frontend Machine Coding Interview Questions](https://www.frontendgeek.com/frontend-interview/machine-coding-interview) in React JS including the common features to implement and key features to cover. Also includes the Advance or optional tags for features.

## Table of Contents

- [Beginner Level Machine Coding Questions](#beginner-level-machine-coding-questions)
  - [1. Increment/Decrement Counter](#1-incrementdecrement-counter)
  - [2. Responsive Grid](#2-responsive-grid)
  - [3. Countdown Widget](#3-countdown-widget)
  - [4. Accordion (Static or Dynamic)](#4-accordion-static-or-dynamic)
  - [5. Responsive Menu/Nav Bar](#5-responsive-menunav-bar)
  - [6. E-Comm Catalog View (Dynamic from API)](#6-e-comm-catalog-view-dynamic-from-api)
- [Intermediate Level Machine Coding Questions](#intermediate-level-machine-coding-questions)
  - [7. Todo Application](#7-todo-application)
  - [8. News Feed / Infinite Scrolling](#8-news-feed--infinite-scrolling)
  - [9. Pagination Implementation](#9-pagination-implementation)
  - [10. Auto-Complete Search / Type-Ahead Search](#10-auto-complete-search--type-ahead-search)
  - [11. Star Rating](#11-star-rating)
  - [12. Image Carousel](#12-image-carousel)
  - [13. Toast Notification](#13-toast-notification)
  - [14. Tab Component (Static or Dynamic)](#14-tab-component-static-or-dynamic)
  - [15. Context Menu](#15-context-menu)
  - [16. Progress Bar Component](#16-progress-bar-component)
  - [17. Modal Component](#17-modal-component)
  - [18. Theme Toggle Switch](#18-theme-toggle-switch)
  - [19. OTP Input](#19-otp-input)
  - [20. Checkout Page](#20-checkout-page)
  - [21. Chips Input](#21-chips-input)
- [Advanced Level Machine Coding Questions](#advanced-level-machine-coding-questions)
  - [22. Multi-Step Form](#22-multi-step-form)
  - [23. Tree / Folder Navigation](#23-tree--folder-navigation)
  - [24. Comment View / Multi-level Comments](#24-comment-view--multi-level-comments)
  - [25. Checkbox Folder Selection](#25-checkbox-folder-selection)
  - [26. Kanban Board](#26-kanban-board)
  - [27. Tic-tac-toe Game](#27-tic-tac-toe-game)
  - [28. Calendar View](#28-calendar-view)
  - [29. Email Client View](#29-email-client-view)
  - [30. Chat Application Interface](#30-chat-application-interface)



## Beginner Level Machine Coding Questions

### 1. Increment/Decrement Counter
A basic counter component that allows users to increase or decrease a numeric value by clicking buttons.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview)

#### Common Features To Implement:
  - Simple increment and decrement buttons
  - Display of the current count value
  - Prevent count from going negative (optional)
  - Ability to reset counter (optional)
  - Custom step size (e.g., increment/decrement by more than 1)
  - Button disabled state when minimum/maximum limits reached
  - State lifting (parent manages value; pass as prop)
  - Unit/integration testing of increment/decrement logic

#### Key Concepts to Cover:
  - React <code>useState</code> for state management
  - Event handling in React (<code>onClick</code>)
  - Component props and default props
  - Conditional rendering and button disabling
  - Component composition and reusability
  - Type checking with PropTypes or TypeScript (optional)
  - Accessibility basics (ARIA labels, roles, keyboard nav)

[↑ Back to Top](#table-of-contents)

---

### 2. Responsive Grid
A flexible grid layout component that adapts to different screen sizes, organizing content in responsive columns with customizable spacing and breakpoints.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview)

#### Common Features To Implement:
  - Grid layout that adapts to various screen sizes with Responsive breakpoints (mobile, tablet, desktop)
  - Customizable number of columns
  - Support for both fixed and fluid grid containers
  - Accessibility: Proper aria roles and keyboard navigation
  - Unit/integration testing for layout logic and reflow

#### Key Concepts to Cover:
  - CSS Grid and/or Flexbox basics in React
  - Passing layout settings as props (columns, gap, breakpoints)
  - Conditional classNames or inline styles based on props/screen size
  - Mapping over collections to create grid items
  - Reusability via generic Grid and GridItem components
  - Accessibility and semantic HTML for grids (e.g., <code>role="grid"</code>)

[↑ Back to Top](#table-of-contents)

---

### 3. Countdown Widget
A timer component that counts down from a target date/time or duration, displaying the remaining time in days, hours, minutes, and seconds with real-time updates.[View more resources on FrontendGeek](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#countdown-timer)

#### Common Features To Implement:
  - Set target date/time or duration for countdown
  - Display days, hours, minutes, and seconds remaining
  - Visual timer that updates every second
  - Format time values (e.g., pad single digits with zero)
  - Pause/resume functionality (optional)
  - Reset countdown to initial value
  - Visual indicators when countdown reaches zero (alerts, animations)
  - **Advance**: Customizable display format (show/hide specific units)
  - **Advance**: Handle timezone differences
  - Unit/integration testing for time calculations

#### Key Concepts to Cover:
  - React <code>useState</code> and <code>useEffect</code> hooks
  - <code>setInterval</code> and <code>clearInterval</code> for timers (Important)
  - Component cleanup in <code>useEffect</code> (prevent memory leaks)
  - Date manipulation and time calculations
  - Conditional rendering based on countdown state
  - **Advance**: Performance optimization (avoid unnecessary re-renders)

[↑ Back to Top](#table-of-contents)

---

### 4. Accordion (Static or Dynamic)
A collapsible content component that allows users to expand and collapse multiple sections, commonly used for FAQs, menus, or grouped information displays.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#accordion)

#### Common Features To Implement:
  - Multiple collapsible sections with headers
  - Expand/collapse on header(icon) click
  - Extra: Smooth animations for opening/closing
  - Single or multiple sections open at once (accordion vs. multi-select)
  - Icons indicating open/closed state (chevrons, plus/minus)
  - Extra: Accessibility: ARIA attributes (aria-expanded, aria-controls)
  - Extra: Keyboard navigation support (Enter, Space, Arrow keys)
  - **Advance**: Disable specific accordion items
  - **Advance**: Dynamic content rendering (fetch data on expand)
  - **Advance**: Nested accordions (optional)
  - Unit/integration testing for expand/collapse logic

#### Key Concepts to Cover:
  - React state management for tracking open/closed items - <code>useState()</code>
  - Conditional rendering and CSS transitions/animations
  - Event delegation and click handling
  - Props drilling or context for nested components
  - Controlled vs. uncontrolled components
  - CSS classes and inline styles for animations
  - Accessibility: ARIA attributes and keyboard events
  - Component composition (Accordion, AccordionItem, AccordionHeader)

[↑ Back to Top](#table-of-contents)

---

### 5. Responsive Menu/Nav Bar
A navigation component that transforms from a horizontal menu on desktop to a hamburger menu on mobile devices with active route highlighting (Smooth animation if required).
[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#menu-bar---responsive)

#### Common Features To Implement:
  - Horizontal navigation menu on desktop
  - Hamburger menu icon on mobile/tablet
  - Slide-in or dropdown menu for mobile view
  - Active route/state highlighting
  - Logo and branding elements
  - Close button in mobile menu
  - Smooth transitions and animations
  - Responsive breakpoints (mobile-first approach)
  - Submenu/nested navigation support
  - Click outside to close mobile menu
  - **Advance**: Sticky/fixed navbar option
  - **Advance**: Keyboard navigation and focus management
  - Accessibility: ARIA labels, roles, keyboard shortcuts

#### Key Concepts to Cover:
  - CSS media queries and responsive design
  - React <code>useState</code> for menu open/closed state
  - Conditional rendering based on screen size (useWindowSize hook)
  - Event handlers for click outside detection
  - CSS transitions and transforms for animations
  - Flexbox for layout (Important)
  - Router integration (activeLink styling)
  - Overlay/modal-like menus (optional)
  - Accessibility: focus trapping, ARIA attributes

[↑ Back to Top](#table-of-contents)

---

### 6. E-Comm Catalog View (Dynamic from API)
A product catalog component that displays items fetched from an API, with filtering, sorting, search, and pagination capabilities for e-commerce applications.

**More Resources:** [View detailed guide on FrontendGeek](https://www.frontendgeek.com/frontend-interview/machine-coding-interview)

#### Common Features To Implement:
  - Display product grid/list from API data
  - Loading states and skeleton screens
  - Error handling and retry mechanisms
  - Product image, title, price, and description
  - Sorting options (price, name, rating, popularity)
  - Filtering by category, price range, brand
  - Search functionality
  - Responsive grid layout (2-4 columns based on screen)
  - Product detail modal or navigation
  - Empty state when no products match filters
  - **Advance**: Pagination or infinite scroll
  - **Optional**: Add to cart functionality
  - **Advance**: URL state management (preserve filters in URL)

#### Key Concepts to Cover:
  - Fetch API for API calls
  - React <code>useEffect</code> for data fetching
  - Loading, error, and success states
  - Array methods: <code>filter</code>, <code>sort</code>, <code>map</code>
  - Controlled inputs for search and filters
  - State management for filters, sort, and pagination
  - Memoization with <code>useMemo</code> for filtered/sorted lists
  - Component composition (ProductCard, FilterBar, SortDropdown)
  - Error boundaries (optional)
  - Debouncing search input (optional)

[↑ Back to Top](#table-of-contents)

---

## Intermediate Level Machine Coding Questions

### 7. Todo Application
A task management application that allows users to add, edit, delete, and filter todo items, with persistence and keyboard shortcuts support.[More Resources on FrontendGeek](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#todo-app)

#### Common Features To Implement:
  - Add new todo items
  - Mark todos as complete/incomplete
  - Delete individual todos
  - Edit existing todos (inline editing)
  - Filter todos (All, Active, Completed)
  - Clear all completed todos
  - Toggle all todos complete
  - Persist todos (localStorage or API)
  - Count of active todos
  - **Optional**: Keyboard shortcuts (Enter to add, Escape to cancel)
  - **Advance**: Drag and drop to reorder
  - **Advance**: Due dates and priorities
  - Accessibility: ARIA labels, keyboard navigation

#### Key Concepts to Cover:
  - CRUD operations in React
  - Complex state management (<code>useState</code> with arrays/objects)
  - Array manipulation (add, update, delete, filter)
  - Controlled inputs and forms
  - localStorage for persistence
  - Unique ID generation (UUID or timestamp)
  - Conditional rendering for filters
  - Component composition (TodoItem, TodoList, TodoForm)
  - State lifting and prop drilling
  - Custom hooks for todo logic (optional)

[↑ Back to Top](#table-of-contents)

---

### 8. News Feed / Infinite Scrolling
A feed component that automatically loads more content as users scroll, displaying posts with engagement features and infinite scrolling.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#infinite-scroll)

#### Common Features To Implement:
  - fetch API to Load and display feed items
  - Automatic loading when user scrolls near bottom or react to bottom
  - Loading indicators (spinner, skeleton)
  - Virtualization: Virtual scrolling for large lists
  - Error handling and retry
  - Image lazy loading
  - **Optional**: Click to view full post
  - **Advance**: Infinite scroll threshold customization

#### Key Concepts to Cover:
  - <code>useEffect</code> and <code>useRef</code> for scroll detection
  - <code>Intersection Observer API</code> or scroll event listeners
  - API pagination (offset/limit or cursor-based)
  - Managing paginated state (page, hasMore, loading)
  - Performance: memoization with <code>React.memo</code> and <code>useMemo</code>
  - Debouncing scroll events
  - Cleanup of event listeners and observers
  - Optimistic UI updates
  - Error boundaries and error states

[↑ Back to Top](#table-of-contents)

---

### 9. Pagination Implementation
A pagination component that allows users to navigate through large datasets by displaying page numbers with prev/next controls and ellipsis for large page ranges.[More Resources on FrontendGeek](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#pagination)

#### Common Features To Implement:
  - Display page numbers or prev/next buttons
  - Jump to first/last page
  - Current page highlighting
  - Items per page selector
  - Total items count display
  - URL synchronization (page in query params)
  - Keyboard navigation (arrow keys)
  - Disable prev/next at boundaries
  - Responsive design (fewer page numbers on mobile)
  - Loading state during page transitions
  - **Optional**: Ellipsis for large page ranges

#### Key Concepts to Cover:
  - Calculating total pages from total items and items per page
  - Array slicing for current page data
  - State management for current page and items per page
  - Generating page number arrays with ellipsis logic
  - URLSearchParams for URL state management
  - Conditional rendering for page numbers
  - Event handling for page navigation
  - Memoization for page calculations
  - Accessible pagination (ARIA labels, keyboard events)

[↑ Back to Top](#table-of-contents)

---

### 10. Auto-Complete Search / Type-Ahead Search
A search component that provides real-time suggestions as users type, with debounced API calls, keyboard navigation, and highlighted matching text.[View detailed guide on FrontendGeek](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#auto-complete-search-|-typeahead-search)

#### Common Features To Implement:
  - Search input field
  - Dropdown suggestions list
  - Highlight matching text in suggestions
  - Keyboard navigation (Arrow keys, Enter, Escape)
  - Debounced API calls
  - Loading state during search
  - Empty state when no results
  - Click outside to close dropdown
  - Recent searches (localStorage)
  - Minimum character threshold before searching
  - Show/hide dropdown based on focus and results

#### Key Concepts to Cover:
  - Controlled input component
  - Debouncing user input (<code>useDebounce</code> hook or custom)
  - API calls with <code>fetch</code> or <code>axios</code>
  - Handling async operations and race conditions
  - Managing dropdown open/closed state
  - Highlighting text matches (using regex)
  - Keyboard event handling (onKeyDown)
  - Click outside detection (useRef, useEffect)
  - **Advance**: AbortController for canceling requests

[↑ Back to Top](#table-of-contents)

---

### 11. Star Rating
An interactive rating component with clickable stars that allows users to select and display ratin.[More Resources on FrontendGeek](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#star-component)

#### Common Features To Implement:
  - Clickable stars (1-5 rating)
  - Hover effect to preview rating
  - Display current rating
  - Read-only mode
  - Show rating value (example - "4.2 out of 5")
  - Customizable number of stars
  - **Advance**: Size variants (small, medium, large)
  - **Accessibility**: ARIA attributes, keyboard navigation
  - **Advance**: Half-star ratings

#### Key Concepts to Cover:
  - Managing rating state (<code>useState</code>)
  - Mouse events (onClick, onMouseEnter, onMouseLeave)
  - Conditional rendering of filled/empty/half stars
  - Props for controlled/uncontrolled components
  - Inline styles or CSS classes for star colors
  - Array methods to generate star elements
  - Calculating fill percentage for visual representation
  - Event handlers for hover and click interactions

[↑ Back to Top](#table-of-contents)

---

### 12. Image Carousel
A slideshow component that displays multiple images sequentially with navigation controls, auto-play functionality, and smooth transitions between images.

#### Common Features To Implement:
  - Display multiple images in sequence
  - Previous/Next navigation buttons
  - Dot indicators showing current image
  - Smooth transitions (fade, slide)
  - Keyboard navigation (Arrow keys)
  - Lazy loading images
  - **Advance**: Auto-play with pause on hover
  - **Advance**: Infinite loop (wrap around)
  - **Advance**: Fullscreen mode (optional)
  - **Advance**: Responsive image sizing

#### Key Concepts to Cover:
  - <code>useState</code> for current image index
  - <code>useEffect</code> with <code>setInterval</code> for auto-play
  - Cleanup intervals on unmount
  - Array manipulation (increment/decrement with bounds)
  - CSS transitions or transforms for animations
  - Conditional rendering for indicators and navigation
  - Touch event handlers (touchStart, touchEnd) for swipe
  - Image optimization and lazy loading
  - Keyboard event handling

[↑ Back to Top](#table-of-contents)

---

### 13. Toast Notification
A notification system that displays temporary messages with different types (success, error, warning), auto-dismiss functionality, and stack management for multiple toasts.[View detailed guide on FrontendGeek](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#toast-notification)

#### Common Features To Implement:
  - Show toast messages with different types (success, error, warning, info)
  - Auto-dismiss after duration
  - Manual dismiss button (X icon)
  - Stack multiple toasts
  - Slide-in/slide-out animations
  - Customizable position (top-right, bottom-left, etc.)
  - Icon or emoji per toast type
  - Progress bar showing remaining time
  - Pause on hover
  - Queue management (limit visible toasts)
  - Accessibility: ARIA live regions

#### Key Concepts to Cover:
  - Portal for rendering outside component tree
  - State management for toast queue (array of toasts)
  - <code>useEffect</code> with timeout for auto-dismiss
  - Unique ID generation for each toast
  - Adding/removing toasts from queue
  - CSS animations and transitions
  - Context API or state management for global toast access
  - Position-based styling (absolute/fixed positioning)

[↑ Back to Top](#table-of-contents)

---

### 14. Tab Component (Static or Dynamic)
A tabbed interface component that organizes content into multiple panels, allowing users to switch between different views with keyboard navigation support.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#tab-bar)

#### Common Features To Implement:
  - Multiple tabs with labels
  - Active tab highlighting
  - Tab content panel display
  - Keyboard navigation (Arrow keys, Home, End)
  - Disabled tabs
  - Icon support in tabs
  - Lazy loading tab content (optional)
  - Scrollable tabs for many items (optional)
  - Vertical tabs layout (optional)
  - URL hash/query for active tab (optional)
  - Accessibility: ARIA tabs pattern

#### Key Concepts to Cover:
  - State management for active tab index
  - Conditional rendering of tab panels
  - Array mapping to generate tabs and panels
  - Keyboard event handling
  - CSS for tab styling and active states
  - Component composition (Tabs, TabList, Tab, TabPanel)
  - Props interface design
  - Controlled vs. uncontrolled component pattern

[↑ Back to Top](#table-of-contents)

---

### 15. Context Menu
A right-click menu component that appears at the cursor position, providing contextual actions with keyboard navigation and click-outside-to-close functionality.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#popover)

#### Common Features To Implement:
  - Right-click to show menu
  - Menu items with labels and icons
  - Menu positioning near cursor
  - Click outside to close
  - Keyboard navigation (Arrow keys, Enter, Escape)
  - Disabled menu items
  - Separator lines between item groups
  - Nested submenus (optional)
  - Animations (fade-in, slide)
  - Prevent default context menu
  - Accessibility: ARIA roles and keyboard support

#### Key Concepts to Cover:
  - Event handling: <code>onContextMenu</code>, <code>preventDefault</code>
  - Portal for rendering menu
  - State for menu visibility and position
  - Calculating menu position (mouse coordinates)
  - Click outside detection
  - Keyboard event handlers
  - Focus management
  - Positioning logic (prevent overflow outside viewport)

[↑ Back to Top](#table-of-contents)

---

### 16. Progress Bar Component
A visual indicator component that displays the completion status of a process, showing progress from 0-100% with animated updates and variant styles.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#pogress-bar)

#### Common Features To Implement:
  - Visual progress indicator (0-100%)
  - Animated progress updates
  - Label showing percentage or status text
  - Different styles (linear, circular)
  - Color variants (success, warning, error, info)
  - Size variants (small, medium, large)
  - Striped/animated pattern option
  - Buffer/secondary progress (optional)
  - Indeterminate mode (loading spinner)
  - Accessibility: ARIA attributes (role="progressbar")

#### Key Concepts to Cover:
  - Props for progress value (0-100)
  - CSS transitions for smooth animations
  - Inline styles or CSS classes for width/percentage
  - Conditional styling based on progress value
  - SVG for circular progress (optional)
  - Component variants with props
  - Accessibility: aria-valuenow, aria-valuemin, aria-valuemax

[↑ Back to Top](#table-of-contents)

---

### 17. Modal Component
A dialog component that overlays the main content, displaying focused information or forms with backdrop, focus trapping, and accessibility features.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#modal-component)

#### Common Features To Implement:
  - Overlay/backdrop
  - Centered modal dialog
  - Close button (X icon)
  - Close on backdrop click
  - Close on Escape key
  - Focus trap (keep focus inside modal)
  - Return focus to trigger element on close
  - Modal title and body content
  - Footer with action buttons
  - Size variants (small, medium, large, fullscreen)
  - Prevent body scroll when open
  - Animation (fade-in, scale)
  - Nested modals support (optional)
  - Accessibility: ARIA modal pattern

#### Key Concepts to Cover:
  - Portal for rendering outside DOM hierarchy
  - State management for open/closed
  - Event handlers (onClick, onKeyDown)
  - Focus management and focus trap
  - CSS for overlay and modal positioning
  - Body scroll lock
  - Component composition (Modal, ModalHeader, ModalBody, ModalFooter)
  - Context API for modal state (optional)

[↑ Back to Top](#table-of-contents)

---

### 18. Theme Toggle Switch
A theme switcher component that allows users to toggle between light and dark modes, persisting preferences and detecting system theme settings.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#light-&-dark-theme)

#### Common Features To Implement:
  - Toggle between light and dark themes
  - Persist theme preference (localStorage)
  - System preference detection (prefers-color-scheme)
  - Smooth transition between themes
  - Apply theme to entire app (CSS variables or Context)
  - Icon indicators (sun/moon icons)
  - Toggle button/switch UI
  - Respect system theme initially (optional)
  - Multiple theme support (beyond just light/dark)

#### Key Concepts to Cover:
  - CSS custom properties (CSS variables) for theming
  - Context API for theme state management
  - localStorage for persistence
  - <code>useEffect</code> to apply theme class to document
  - Media query: <code>matchMedia</code> for system preference
  - Conditional rendering based on theme
  - Toggle component (controlled/uncontrolled)

[↑ Back to Top](#table-of-contents)

---

### 19. OTP Input
A multi-digit input component for one-time passwords, with auto-focus navigation between fields, paste detection, and keyboard-only numeric input.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#otp-input-design)

#### Common Features To Implement:
  - Multiple input fields (typically 4-6 digits)
  - Auto-focus next input on entry
  - Auto-paste detection (paste OTP code)
  - Backspace to go to previous input
  - Only numeric input allowed
  - Focus management and keyboard navigation
  - Visual feedback for filled/empty states
  - Error state display
  - Resend OTP functionality (optional)
  - Timer for resend countdown (optional)
  - Accessibility: ARIA labels, input mode

#### Key Concepts to Cover:
  - Multiple refs or array of refs (<code>useRef</code>)
  - Controlled inputs with state array
  - Event handlers: onChange, onKeyDown, onPaste
  - Focus management (<code>focus()</code> method)
  - Input validation (numeric only)
  - String manipulation for paste handling
  - Component state management for OTP values

[↑ Back to Top](#table-of-contents)

---

### 20. Checkout Page
A comprehensive checkout form component with multiple sections for shipping, billing, and payment, including validation, order summary, and calculations.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#e-commerce-app-view)

#### Common Features To Implement:
  - Multiple form sections (shipping, billing, payment)
  - Form validation (required fields, email format, card number)
  - Error messages display
  - Order summary with items and totals
  - Shipping address form
  - Payment method selection
  - Apply discount/promo code
  - Calculate taxes and shipping costs
  - Responsive layout
  - Loading state during submission
  - Success/error handling
  - Save form data (localStorage, optional)

#### Key Concepts to Cover:
  - Complex form state management
  - Form validation (controlled inputs, validation functions)
  - Error state handling
  - Conditional rendering based on form state
  - Calculations (totals, taxes, discounts)
  - Form submission handling (onSubmit, preventDefault)
  - Component composition (ShippingForm, PaymentForm, OrderSummary)
  - State lifting for shared data

[↑ Back to Top](#table-of-contents)

---

### 21. Chips Input
An input component that allows users to add multiple tag-like chips by typing and pressing Enter, with individual removal and duplicate prevention.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#chips-input)

#### Common Features To Implement:
  - Add chips by typing and pressing Enter/comma
  - Remove chips (X button)
  - Edit existing chips (optional)
  - Visual chip styling with rounded corners
  - Duplicate prevention
  - Max chips limit (optional)
  - Keyboard navigation (Arrow keys, Delete)
  - Focus management
  - Disabled state
  - Different chip variants (colors, sizes)
  - Validation (e.g., email format for email chips)

#### Key Concepts to Cover:
  - Managing array of chip values in state
  - Array manipulation (add, remove, update)
  - Controlled input component
  - Event handlers (onKeyDown for Enter/Backspace)
  - Conditional rendering for chips
  - Inline editing state (optional)
  - Focus management and refs
  - Duplicate detection logic

[↑ Back to Top](#table-of-contents)

---

## Advanced Level Machine Coding Questions

### 22. Multi-Step Form
A wizard-style form component that breaks complex forms into multiple steps with progress indicators, step validation, and navigation controls.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#multi-step-form)

#### Common Features To Implement:
  - Multiple form steps/pages
  - Progress indicator (step numbers, progress bar)
  - Navigation between steps (Next, Previous, Skip)
  - Step validation before proceeding
  - Summary/Review step before submission
  - Save form data as user progresses
  - Go to specific step (optional)
  - Step completion indicators
  - Responsive design
  - Error handling per step
  - Accessibility: ARIA attributes for wizard pattern

#### Key Concepts to Cover:
  - State management for current step and form data
  - Step validation logic
  - Conditional rendering based on current step
  - Navigation logic (increment/decrement step)
  - Data persistence between steps
  - Form state management (controlled inputs)
  - Progress calculation
  - Component composition (StepIndicator, StepContent, NavigationButtons)

[↑ Back to Top](#table-of-contents)

---

### 23. Tree / Folder Navigation
A hierarchical tree component that displays nested folder/file structures with expand/collapse functionality, search capabilities, and keyboard navigation.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#tree-view-/-folder-view)

#### Common Features To Implement:
  - Hierarchical tree structure display
  - Expand/collapse nodes (folders)
  - Nested levels (indentation)
  - Icons for folders and files
  - Click to select nodes
  - Search/filter nodes
  - Lazy loading children (optional)
  - Drag and drop (optional)
  - Checkbox selection (optional)
  - Keyboard navigation (Arrow keys, Space, Enter)
  - Accessibility: ARIA tree pattern

#### Key Concepts to Cover:
  - Recursive component rendering
  - Tree data structure (nested objects/arrays)
  - State management for expanded/collapsed nodes
  - Recursive functions for tree traversal
  - Deep cloning for immutable updates
  - Event bubbling and propagation
  - DFS/BFS algorithms for search (optional)
  - Memoization for performance (optional)

[↑ Back to Top](#table-of-contents)

---

### 24. Comment View / Multi-level Comments
A nested comment system that displays threaded conversations with replies, voting functionality, and collapsible threads with recursive rendering.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#comment-view-(multi-level))

#### Common Features To Implement:
  - Display nested comments (replies)
  - Add new comments and replies
  - Edit and delete comments
  - Voting (upvote/downvote) or likes
  - Reply-to functionality
  - Threading visualization (indentation, lines)
  - Collapse/expand comment threads
  - Timestamp display (relative time)
  - User avatars and names
  - Sort options (newest, oldest, most liked)
  - Real-time updates (optional)
  - Character limit and validation

#### Key Concepts to Cover:
  - Recursive component rendering for nested structure
  - Tree/nested data structure management
  - CRUD operations on nested data
  - State management for nested comments
  - Deep update functions (immutable updates)
  - Event handling with parent-child relationships
  - Sorting algorithms for nested data
  - Date formatting and relative time

[↑ Back to Top](#table-of-contents)

---

### 25. Checkbox Folder Selection
A hierarchical checkbox component where parent checkboxes control their children, with indeterminate states and bidirectional state synchronization.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#comment-view-(multi-level))

#### Common Features To Implement:
  - Hierarchical checkbox structure
  - Parent checkbox controls children (check/uncheck all)
  - Child checkbox updates parent state (indeterminate)
  - Indeterminate state visual (dash icon)
  - Expand/collapse folders
  - Select all functionality
  - Count selected items
  - Save selection state
  - Search/filter with selection preservation
  - Keyboard navigation
  - Accessibility: ARIA attributes for treegrid

#### Key Concepts to Cover:
  - Recursive component with checkbox state
  - Tree data structure with selection state
  - Calculating parent state from children (check/uncheck/indeterminate)
  - Bidirectional updates (parent ↔ children)
  - Deep traversal algorithms
  - Immutable state updates for nested structures
  - Indeterminate checkbox state handling
  - Memoization for expensive calculations

[↑ Back to Top](#table-of-contents)

---

### 26. Kanban Board
A drag-and-drop task management board with multiple columns (To Do, In Progress, Done) where cards can be moved between columns with full CRUD operations.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#kanban-board)

#### Common Features To Implement:
  - Multiple columns (To Do, In Progress, Done)
  - Drag and drop cards between columns
  - Add/remove cards
  - Add/remove columns
  - Edit card content
  - Card details (title, description, assignee, due date)
  - Limit cards per column (optional)
  - Column scrolling for many cards
  - Responsive design
  - Persist board state (localStorage/API)
  - Search/filter cards
  - Keyboard shortcuts
  - Accessibility: ARIA drag and drop attributes

#### Key Concepts to Cover:
  - HTML5 Drag and Drop API or react-beautiful-dnd
  - State management for columns and cards (array of objects)
  - Drag event handlers (onDragStart, onDragOver, onDrop)
  - Moving items between arrays (immutable updates)
  - Column and card CRUD operations
  - Responsive layout with CSS Grid or Flexbox
  - State persistence
  - Complex state structure (nested arrays)

[↑ Back to Top](#table-of-contents)

---

### 27. Tic-tac-toe Game
An interactive tic-tac-toe game component with a 3x3 board, turn-based gameplay, win detection algorithms, and game state management.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#games)

#### Common Features To Implement:
  - 3x3 game board
  - Two players (X and O) alternate turns
  - Win detection (rows, columns, diagonals)
  - Draw detection
  - Display current player
  - Game status (playing, won, draw)
  - Reset/New game functionality
  - Game history (undo moves, optional)
  - Highlight winning line
  - Score tracking (optional)
  - AI opponent (optional)
  - Responsive grid layout

#### Key Concepts to Cover:
  - State management for board (2D array or flat array)
  - Turn management (tracking current player)
  - Win condition algorithms
  - Immutable updates (don't mutate state)
  - Conditional rendering for game status
  - Event handling for square clicks
  - Algorithm for win detection
  - Minimax algorithm for AI (optional)

[↑ Back to Top](#table-of-contents)

---

### 28. Calendar View
A calendar component that displays a monthly grid view with date navigation, event display, and the ability to view/add events on specific dates.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#calendar-view)

#### Common Features To Implement:
  - Monthly calendar grid display
  - Navigate between months (prev/next)
  - Display current month and year
  - Highlight today's date
  - Show events/appointments on dates
  - Click date to view/add events
  - Different calendar views (month, week, day)
  - Date range selection (optional)
  - Mark weekends differently
  - Responsive design
  - Keyboard navigation
  - Multiple event types with colors
  - Recurring events (optional)

#### Key Concepts to Cover:
  - Date manipulation (Date object, date-fns, or dayjs)
  - Generating calendar grid (first day of month, days in month)
  - Month navigation (add/subtract months)
  - Managing events data (group by date)
  - State management for selected date and events
  - Array manipulation for calendar grid generation
  - Conditional rendering for dates and events
  - Date formatting and localization

[↑ Back to Top](#table-of-contents)

---

### 29. Email Client View
An email interface component with inbox list, email detail view, compose functionality, filtering, sorting, and folder navigation capabilities.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#email-inbox-view)

#### Common Features To Implement:
  - Email list/inbox view
  - Email detail view
  - Email composition modal/form
  - Mark as read/unread
  - Star/favorite emails
  - Delete emails
  - Search/filter emails
  - Sort emails (date, sender, subject)
  - Folder/category navigation (Inbox, Sent, Trash)
  - Pagination or infinite scroll
  - Attachment indicators
  - Responsive layout (list + detail or split view)
  - Loading states
  - Empty states

#### Key Concepts to Cover:
  - Complex state management (emails array, filters, sort)
  - CRUD operations on email list
  - Filtering and sorting logic
  - Routing or state for email detail view
  - Form handling for compose
  - Array methods (filter, sort, map, find)
  - Component composition (EmailList, EmailItem, EmailDetail, ComposeForm)
  - State lifting and prop drilling
  - URL state management (optional)

[↑ Back to Top](#table-of-contents)

---

### 30. Chat Application Interface
A real-time chat interface component with message list, input field, auto-scroll functionality, typing indicators, and message status tracking.[More Resources](https://www.frontendgeek.com/frontend-interview/machine-coding-interview#messaging-interface)

#### Common Features To Implement:
  - Chat message list with scroll to bottom
  - Message input and send button
  - User messages vs. other messages (different styling)
  - Timestamp display (relative or absolute)
  - Typing indicators (optional)
  - Online/offline status (optional)
  - Message reactions (optional)
  - File/image attachments (optional)
  - Emoji picker (optional)
  - Auto-scroll to new messages
  - Message status (sending, sent, delivered, read)
  - Real-time updates (WebSocket simulation)
  - Responsive design
  - Accessibility: ARIA live regions for new messages

#### Key Concepts to Cover:
  - State management for messages array
  - Adding messages to list (immutable updates)
  - Scroll management (scrollIntoView, scrollTop)
  - Real-time updates (setInterval simulation or WebSocket)
  - Controlled input for message text
  - Conditional rendering for message types
  - Date formatting for timestamps
  - Performance: memoization, virtual scrolling (optional)
  - Component composition (ChatWindow, MessageList, MessageInput, MessageBubble)

[↑ Back to Top](#table-of-contents)