# Acceptance Criteria

## User Story: As a site user, I want to navigate easily throughout the website so that I can find the information I need.

---

### Navigation Bar Acceptance Criteria:

#### 1. Navigation Bar Structure
- **Given** I am on any page of the website
- **When** I look at the top of the page
- **Then** I should see a navigation bar with menu items: Home, Services, About Us, Contact
- **And** the navigation bar should be fixed at the top of the page

#### 2. Navigation Bar on Mobile
- **Given** I am on a mobile device (screen width < 768px)
- **When** I view the website
- **Then** I should see a hamburger menu icon
- **And** when I click the hamburger menu, all navigation items should be visible

#### 3. Active Page Indication
- **Given** I am on any page
- **When** I look at the navigation bar
- **Then** the current page should be visually highlighted in the navigation menu

---

### Footer Acceptance Criteria:

#### 4. Footer Navigation Links
- **Given** I am at the bottom of any page
- **When** I look at the footer
- **Then** I should see quick links to: Services, About Us, Contact
- **And** all footer links should navigate to the correct pages

#### 5. Footer Contact Information
- **Given** I am viewing the footer
- **When** I need contact details
- **Then** I should see the spa's phone number, email, and address
- **And** the phone number should be clickable on mobile devices

---

### Definition of Done:
- [ ] Navigation bar displays on all pages with correct menu items
- [ ] Mobile hamburger menu functions properly
- [ ] Active page is highlighted in navigation
- [ ] Footer contains working navigation links
- [ ] Footer displays complete contact information
- [ ] All links are functional and tested
