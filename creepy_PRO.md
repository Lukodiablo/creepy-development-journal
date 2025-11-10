🛡️ Creepy Bot Pro Features & Advanced Moderation Wiki
The Complete Guide to Professional Discord Server Management
📖 Table of Contents
Pro Features Overview
Advanced Moderation Trinity
Anti-Spam Protection System
Raid Protection & Emergency Controls
Elite User Case Files & Auditing
Premium Dashboard Features
Server Management Tools
Automated Systems
Analytics & Insights
Setup & Configuration Guide
🎯 Pro Features Overview
Creepy Bot Pro transforms your Discord server into a professional-grade community with enterprise-level moderation, advanced automation, and comprehensive management tools.
What's Included in Pro:
✅ Advanced Moderation Trinity (Configuration, Execution, Auditing)
✅ Intelligent Anti-Spam System with severity-based responses
✅ Automated Raid Protection with emergency lockdown
✅ Elite User Case Files with complete moderation history
✅ Professional Dashboard with real-time controls
✅ Advanced Server Tools (Temp channels, announcements, embeds)
✅ Age Verification System with automatic enforcement
✅ Comprehensive Analytics and moderation insights
✅ Priority Support and feature requests
🛡️ Advanced Moderation Trinity
The cornerstone of Creepy Pro is our Three-Pillar Moderation System that provides complete server protection and transparency.
Pillar 1: Configuration (Settings & Rules)
Professional-grade configuration system with granular controls:
Severity System: 5-level escalation (Minimal → Low → Moderate → Aggressive → Nuclear)
Role-Based Permissions: Fine-grained access control for moderation features
Custom Thresholds: Configurable limits for all detection systems
Integration Settings: Seamless connection between all moderation tools
Pillar 2: Execution (Active Protection)
Real-time protection systems that work 24/7:
Smart Detection Algorithms: AI-powered spam and raid detection
Automated Response System: Instant action based on severity settings
Manual Override Controls: Emergency buttons for immediate intervention
Escalation Tracking: Automatic severity increases for repeat offenders
Pillar 3: Auditing (Transparency & Accountability)
Complete transparency and historical tracking:
Permanent Case Files: Comprehensive user infraction records
Public Moderation Logs: Transparent action logging with formatted embeds
Advanced Search Tools: Find any user or action instantly
Statistical Analytics: Server-wide moderation insights and trends
🚫 Anti-Spam Protection System
Smart Detection Engine
Our advanced anti-spam system detects multiple threat vectors:
Detection Categories:
Discord Invites: Automatically detects and blocks server invite links
External Links: Configurable blocking of non-Discord URLs
Mass Mentions: Prevents @everyone/@here spam and mass user mentions
Message Flooding: Detects rapid message posting patterns
Duplicate Content: Identifies repeated message spam
Severity-Based Response System:
Minimal: Delete message + warning
Low: Delete + direct message warning
Moderate: Delete + 5-minute timeout + warning
Aggressive: Delete + kick user + notification
Nuclear: Delete + ban user + notification
Configuration Options:
code
Yaml
Anti-Spam Settings:
├── Enable/Disable Protection
├── Block Discord Invites: ✓/✗
├── Block External Links: ✓/✗
├── Mass Mention Threshold: 1-10 mentions
├── Fast Message Limit: 1-20 messages/minute
├── Severity Level: Minimal → Nuclear
└── Exempt Roles: Select roles to bypass
Real-Time Features:
Instant Detection: Sub-second response time
Smart Filtering: Context-aware detection to avoid false positives
Whitelist Support: Trusted domains and users bypass detection
Learning Algorithm: Adapts to server-specific patterns
🛡️ Raid Protection & Emergency Controls
Intelligent Raid Detection
Advanced monitoring system that tracks suspicious activity patterns:
Detection Metrics:
Join Rate Monitoring: Tracks users joining per time window
Pattern Analysis: Identifies coordinated mass joins
Account Age Verification: Flags new/suspicious accounts
Behavior Correlation: Links related suspicious activities
Auto-Lockdown System:
Threshold Configuration: Set custom join limits (5-50 users)
Time Window Settings: Configure detection period (30s-10min)
Lockdown Duration: Automatic unlock after set time (5min-24hr)
Action Customization: Choose lockdown behaviors
Emergency Control Panel
Manual override controls for immediate response:
Panic Controls:
🚨 Emergency Lockdown: Instant server lockdown button
⏰ Duration Override: Extend or shorten active lockdowns
🔓 Manual Unlock: Immediate lockdown release
📢 Alert Broadcast: Send emergency notifications
Lockdown Actions:
Server Lock: Prevent new member joins
Channel Restrictions: Limit new member permissions
Role Assignment: Auto-assign restricted roles to new joins
Moderator Alerts: Ping staff roles and send channel notifications
Advanced Features:
code
Yaml
Raid Protection Settings:
├── Auto-Lockdown: ✓/✗
├── Join Threshold: 5-50 users
├── Time Window: 30s-10min
├── Lockdown Duration: 5min-24hr
├── Alert Channel: Select notification channel
├── Moderator Role: Choose staff ping role
├── Exempt Roles: Whitelist trusted roles
└── Custom Actions: Lock/Mute/Alert combinations
👤 Elite User Case Files & Auditing
Comprehensive Case File System
Every user gets a permanent moderation record with complete history tracking:
Case File Contents:
User Profile: Discord ID, username history, join date
Infraction Summary: Total actions, severity points, escalation level
Action Timeline: Chronological list of all moderation actions
Moderator Notes: Staff annotations and context
Appeal History: Record of appeals and resolutions
Advanced Search & Filtering:
Username Search: Find users by current or previous names
Discord ID Lookup: Exact user identification
Action Type Filter: Filter by warns, kicks, bans, etc.
Date Range Search: Find actions within specific timeframes
Moderator Filter: View actions by specific staff members
Public Moderation Logs
Transparent logging system with formatted embeds:
Embed Features:
Color Coding: Visual identification by action severity
Action Details: Complete context including reason, duration, moderator
User Information: Avatar, username, Discord ID, account age
Timestamp Tracking: Precise action timing with timezone support
Automod Integration: Clear distinction between manual and automated actions
Log Channel Setup:
code
Yaml
Public Logging Options:
├── Enable Public Logs: ✓/✗
├── Log Channel: Select destination channel
├── Embed Style: Full/Compact/Minimal
├── Action Filtering: Choose which actions to log
├── Staff Privacy: Hide/Show moderator names
└── Auto-Delete: Optional log cleanup after time
Statistical Dashboard
Server-wide analytics and insights:
Key Metrics:
Total Actions: All-time moderation action count
Active Cases: Users with recent infractions
Action Breakdown: Distribution by type (warn/kick/ban)
Trend Analysis: 7/30/90-day activity patterns
Staff Performance: Moderator activity statistics
Resolution Rates: Appeal and case closure metrics
💎 Premium Dashboard Features
Modern Web Interface
Professional dashboard with intuitive controls:
Dashboard Sections:
🏠 Server Overview: Stats, recent activity, quick actions
⚙️ Moderation Settings: Anti-spam, raid protection, severity config
👥 User Management: Search, case files, bulk actions
📊 Analytics: Charts, trends, performance metrics
🔧 Server Tools: Temp channels, announcements, embeds
🛡️ Security: Age verification, role management, audit logs
Real-Time Features:
Live Status Updates: Real-time lockdown status and active protections
Instant Notifications: Desktop alerts for critical events
Mobile Responsive: Full functionality on all devices
Dark/Light Theme: Customizable interface appearance
Role-Based Access: Different permission levels for staff
Advanced Configuration Tools
Granular control over all bot features:
Server Management:
Role Selectors: Visual role picking with permission previews
Channel Management: Category organization and permission setup
Bulk Operations: Mass user actions and configuration imports
Template System: Save and reuse configuration sets
Backup/Restore: Configuration backup and rollback capabilities
🛠️ Server Management Tools
Temporary Channel System
Dynamic channel creation with automatic cleanup:
Features:
Voice Channels: Auto-create private voice rooms
Text Channels: Temporary discussion channels
Duration Control: Set automatic deletion timers (1hr-7days)
Permission Templates: Pre-configured access patterns
Category Organization: Organized channel structure
Configuration:
code
Yaml
Temp Channel Settings:
├── Enable Voice Channels: ✓/✗
├── Enable Text Channels: ✓/✗
├── Max Duration: 1hr-7days
├── Authorized Roles: Select permitted roles
├── Category Placement: Choose organization category
└── Naming Pattern: Customize channel naming
Advanced Announcement System
Professional broadcasting with role management:
Announcement Features:
Rich Embeds: Formatted messages with images and links
Role Pinging: Selective @mentions with cooldown protection
Scheduling: Future message delivery
Templates: Reusable announcement formats
Multi-Channel: Broadcast to multiple channels simultaneously
Safety Features:
Cooldown System: Prevent announcement spam
Role Restrictions: Limit who can create announcements
Content Filtering: Automatic profanity and link checking
Preview Mode: Test announcements before sending
Audit Trail: Complete announcement history
Professional Embed Creator
Visual message designer with advanced formatting:
Embed Capabilities:
Visual Editor: Drag-and-drop message design
Rich Content: Images, videos, links, custom fields
Color Themes: Brand-consistent color schemes
Interactive Elements: Buttons, reactions, forms
Template Library: Pre-made professional designs
🔍 Age Verification System
Account Age Protection
Automatic enforcement of minimum account age requirements:
Verification Features:
Configurable Thresholds: Set minimum account age (1day-1year)
Automatic Actions: Kick or ban new accounts
Grace Period: Temporary roles for borderline accounts
Manual Review: Staff override for legitimate new users
Whitelist System: Trusted user bypasses
Integration Options:
code
Yaml
Age Verification Settings:
├── Enable Protection: ✓/✗
├── Minimum Age: 1day-365days
├── Action Type: Kick/Ban/Role Assignment
├── Grace Period: 0-24 hours
├── Log Channel: Verification notifications
├── Exempt Roles: Bypass verification
└── Appeal Process: Enable user appeals
📊 Analytics & Insights
Server Health Metrics
Comprehensive analytics dashboard with actionable insights:
Key Performance Indicators:
Member Growth: Join/leave trends and retention rates
Activity Levels: Message frequency and engagement metrics
Moderation Load: Action frequency and staff workload
Security Threats: Spam attempts and raid detection stats
Feature Usage: Most popular bot features and commands
Trend Analysis:
Historical Data: Up to 1-year data retention
Predictive Analytics: Trend forecasting and anomaly detection
Comparative Metrics: Month-over-month and year-over-year comparisons
Custom Reports: Generate specific analytics reports
Export Options: CSV and PDF report generation
Advanced Reporting
Professional reporting tools for server administrators:
Report Types:
Moderation Summary: Staff performance and action effectiveness
Security Report: Threat detection and prevention statistics
Growth Analysis: Member acquisition and retention insights
Engagement Metrics: Activity patterns and peak usage times
Feature Adoption: Bot command usage and popular features
⚙️ Setup & Configuration Guide
Initial Pro Setup
Step-by-step guide to activate and configure Pro features:
Step 1: Pro Activation
Purchase Pro Subscription: Select your server tier
Bot Authorization: Grant necessary permissions
Dashboard Access: Login with Discord OAuth
Server Selection: Choose target server
Feature Activation: Enable desired Pro features
Step 2: Core Configuration
Moderation Settings: Configure anti-spam and raid protection
Logging Setup: Choose public log channels
Role Assignment: Set staff and moderation roles
Permission Review: Verify bot permissions
Testing Phase: Test all features in controlled environment
Step 3: Advanced Setup
Severity Calibration: Fine-tune response levels
Custom Templates: Create server-specific configurations
Integration Testing: Verify all systems work together
Staff Training: Educate moderator team on new tools
Monitoring Setup: Configure alerts and notifications
Best Practices
Professional tips for optimal Pro feature usage:
Moderation Best Practices:
Start Conservative: Begin with lower severity levels
Monitor Effectiveness: Track false positive rates
Regular Reviews: Weekly assessment of moderation actions
Staff Coordination: Ensure team understands new tools
Documentation: Maintain server-specific moderation guidelines
Security Recommendations:
Layered Protection: Use multiple security features together
Regular Updates: Keep bot permissions and settings current
Backup Configurations: Save working configurations
Incident Response: Prepare for emergency scenarios
Community Education: Inform members about new protections
🎬 Video Guide Integration
This section will be updated with video links and tutorials following your upcoming video production:
Planned Video Guides:
📹 Pro Features Overview (10-15 minutes)
📹 Anti-Spam Configuration (5-8 minutes)
📹 Raid Protection Setup (8-12 minutes)
📹 User Case Files Tutorial (6-10 minutes)
📹 Dashboard Navigation (12-15 minutes)
📹 Advanced Analytics (8-12 minutes)
📹 Troubleshooting Guide (10-15 minutes)
Interactive Elements:
Timestamps: Direct links to specific topics
Code Examples: Copy-paste configuration snippets
Screenshots: Visual step-by-step guides
FAQ Section: Common questions and solutions
Community Links: Discord support server and forums
🚀 Coming Soon
Planned Pro Features:
AI-Powered Moderation: Machine learning threat detection
Advanced Role Management: Dynamic role assignment system
Custom Commands: Server-specific command creation
Integration Hub: Connect with external services
Mobile App: Native mobile dashboard
Multi-Server Management: Manage multiple servers from one dashboard
📞 Support & Resources
Getting Help:
📚 Documentation: This comprehensive wiki
💬 Support Server: Join our Discord for live help
📧 Priority Support: Pro users get dedicated support
🎥 Video Tutorials: Step-by-step visual guides
📖 Best Practices: Community-driven recommendations
Community Resources:
🌟 Feature Requests: Suggest new Pro features
🐛 Bug Reports: Report issues for priority fixes
💡 Configuration Sharing: Share working setups
🏆 Success Stories: Showcase your server improvements
🤝 Partner Program: Collaborate with Creepy Bot team
