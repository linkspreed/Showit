# v2.2.6 (01 Sep, 2022)
 - ADDED the ability to upload media files directly to spaces, amazon, wasabi and blackaze.
 - ADDED custom endpoint (domain name) for S3, Spaces, Wasabi and Backblaze (CDN support).
 - ADDED chunk upload system, now the video is being chunked while uploading to small parts.
 - ADDED support for lightspeed.
 - FIXED +2 minor bugs.

# v2.2.5 (23 Aug, 2022)
 - ADDED more regions to spaces and amazon s3.
 - FIXED tiktok short links not importing.
 - FIXED DigitalOcean, BackBlaze and Wasabi upload system.
 - FIXED +10 minor bugs.

# v2.2.4 (07 Aug, 2022)
 - ADDED the ability to import videos from TikTok.
 - ADDED BackBlaze storage.
 - ADDED Hindi, Urdu, Chine, Indonesian, Croatian, Hebrew, Bengali, Japanese, Portuguese, Italian, Persian, Swedish, Vietnamese, Danish, Filipino languages.
 - ADDED the ability to mark all messages as read.
 - ADDED time to messages.
 - ADDED load more to message users.
 - ADDED the ability to add video title for live streaming.
 - ADDED cronjob.php file, all background processes are now added to cronjob.php, the file should be added to your server crontab, How to add cronjob?
 - IMPROVED design in few sections.
 - IMPROVED hreflang tags.
 - IMPROVED SEO of whole website.
 - REMOVED 100MB+ from outdated libs and replaced them with cURL, for faster load speeds.
 - REMOVED 10+ outdated files and merged to one file (watch page).
 - REMOVED 13 columns from database, and replaced with faster method (payments).
 - FIXED when you copy a password using the mouse button and paste it in the password field it does not work (password complicity)
 - FIXED 5 PHP warnings and fatel errors.
 - FIXED nginx rules, if you are using nginx, you need to update the nginx.conf of your server with the updated one.
 - FIXED max allowed processes for ffmpeg.
 - FIXED upload issue for files more than 2.5GB.
 - FIXED history page was not updating new watched videos.
 - FIXED no title in 404 pages.
 - FIXED the dollar mark ($) that appear in all Mass Notifications.
 - FIXED autoplay videos repeating the same videos.
 - FIXED reset password was missing the password complicity system.
 - FIXED pro users couldn't set videos as "Featured"
 - FIXED Twitch import was not working.
 - FIXED nodejs CROS problems.
 - FIXED trending page showing videos with 0 views.
 - FIXED points not received if user uploads a new video.
 - FIXED important security exploit in API.
 - FIXED +10 minor bugs.

# v2.2.3 (12 Jul, 2022)
 - ADDED quailty selector to embed video system.
 - FIXED videos playing twice in background.
 - FIXED ads showing on upload/import page, cause design glitch.
 - FIXED shorts title was not updating.
 - FIXED youtube video was not embedable.
 - FIXED embed player size was not fixed.
 - FIXED clicking on channel name in search page takes you to image link instead of channel.
 - FIXED +3 minor bugs.

# v2.2.2 (09 July, 2022) [Stability Update]
 - ADDED the ability to translate dates
 - ADDED the ability to choose player color on embed
 - ADDED category list on homepage
 - UPDATED all PHP libs to latest version & removed unused libs
 - IMPROVED design of shorts on home page and profile
 - IMPROVED design of monetization page
 - IMPROVED design of pro system page
 - IMPROVED design of manage sessions and balance pages
 - IMPROVED design of radio boxes
 - IMPROVED design of playlist models
 - IMPROVED design of history page
 - IMPROVED hover effects on some elements
 - IMPROVED movies page
 - IMPROVED stock videos page
 - IMPROVED speed on top videos page, it was a bit slow
 - FIXED shorts were showing order by last, now by views
 - FIXED ajax load was not working on phones
 - FIXED users couldn't reply to comments on posts
 - FIXED clicking share button on home page wasn't opening the share dialog
 - FIXED private videos were added to sitemap
 - FIXED google login
 - FIXED users weren't able to pay more than $1,000 in wallet
 - FIXED movies search system was broken
 - FIXED blank video on liked videos page showing to some users
 - FIXED +10 minor bugs

# v2.2.1 (30 May, 2022)
 - FIXED title not showing

# v2.2 (28 May, 2022)
 - ADDED the ability to translate terms pages
 - ADDED shorts videos
 - ADDED the ability to remember this device
 - ADDED password complexity system
 - ADDED registeration by first and last name (auto generated username)
 - ADDED user invitation system
 - ADDED new API
 - FIXED few bugs
 - FIXED small XSS vulnerability

# Version 2.1.4 (10 Jan, 2022) [Important Security Patch]
 - FIXED maintenance mode page
 - FIXED upload showing "undefined" using ffmpeg
 - FIXED system adding users as CC in newsletter
 - FIXED important security XSS exploit

# Version 2.1.3 (06 Jan, 2022)
 - ADDED LinkedIn, Vkontakte, Instagram, QQ, WeChat, Discord & Mailru social login
 - FIXED subscription counter
 - UPDATED blog design

# Version 2.1.2 (29 Dec, 2021)
 - ADDED the ability to set video resolutions
 - ADDED noindex meta tag for private videos
 - FIXED auto-play problems in watch page
 - FIXED subscribers page
 - FIXED playlist auto play issue
 - FIXED emojie support on video titles
 - FIXED categories selection on mobile devices
 - FIXED video views was not increasing in embeded videos
 - FIXED progress bar on upload page
 - FIXED thumbnail select issue on upload page
 - FIXED few more minor bugs

# Version 2.1 (2021)
 - ADDED new theme
 - ADDED new video player, plyr.io
 - FIXED 10+ reported bugs
 - FIXED Important security bug

# Version 2.0.3 (2021)
 - FIXED video privacy issue
 - FIXED video image ads count down issue
 - FIXED video cards issue on self hosted videos
 - FIXED SQL injection vulnerability
 - FIXED other minor bugs

# Version 2.0.2 (2021)
 - ADDED support for PHP 8.0+ and MySQL 8.0+

# Version 2.0 (2021)
 - ADDED the ability to turn off chat on live steam
 - ADDED ability to add trailer with movie
 - ADDED ability to restrict a video from embeding while uploading
 - ADDED ability to add texts/cards in specific part of the video
 - ADDED scheduled upload videos in Privacy: Public, Private, Unlisted, Scheduled
 - ADDED subscribe to newsletters
 - ADDED the ability to download your own data from settings page
 - FIXED Important security bug
 - FIXED 5+ important bugs

# Version 1.9 (2021)
 - ADDED the ability to restrict rights of certain user from uploading / importing a video.
 - ADDED new video player (cloudinary)
 - ADDED new live stream system
 - ADDED stock video section
 - ADDED ability to pay per view feature for publisher
 - ADDED ability to re-arrange videos in playlist
 - ADDED ability to set articles as featured on homepage
 - ADDED point system, users can earn points by doing several activities on the site
 - ADDED sticky video player (on scroll)
 - FIXED Important security bug
 - FIXED 5+ important bugs

# Version 1.8.1 (2021)
 - FIXED Important security bug
 - FIXED 5+ important bugs

# Version 1.7.1 (2021)
 - ADDED the ability to send take down notice for specific video
 - ADDED when someone access site first time a popup was added to select specific language
 - ADDED 5+ more APIs
 - FIXED 20+ important bugs

# Version 1.7 (2021)
 - ADDED the ability to set a limit per day for ads
 - ADDED the ability to import videos from ok.ru 
 - ADDED sort by month, week and year in top videos page
 - ADDED gif system for videos (a 4 second gif will show up when user hover on the video thumbnail)
 - ADDED block system, channels can block each other
 - ADDED the ability to import videos to a sub category
 - ADDED Manage sessions
 - ADDED subscription system for channels
 - FIXED 20+ important bugs.

# Version 1.6 (2021)
 - ADDED Movies system
 - ADDED pagination system, now all videos load through pagination system and not through "load more videos" button
 - ADDED the ability to upload a demo video for videos that being sold.
 - ADDED dailymotion monetization system
 - ADDED the ability for users to create and submit articles
 - ADDED the ability for user to transfter funds from earnings to wallet, so they can buy ads from their own earnings
 - ADDED slider to home page
 - FIXED few important bugs on both themes
 - IMPROVED site header in default theme

# Version 1.5 (2021)
 - ADDED video studio, view detailed charts and analytics of videos, views, likes, dislikes, comments and many other features
 - ADDED paid videos system, user can sell his own videos to other viewers
 - ADDED No Upload disk limit for all users, pro users, and for specific users
 - ADDED video seconds on comments, start a video from a spesfic second
 - ADDED Subscription list to the left sidebar
 - ADDED Ajax load, content are loaded faster and smoother
 - ADDED filter system on search page
 - ADDED Two-factor authentication
 - ADDED Identify the speed of the internet and select the quality based on that
 - ADDED Popular Channels To browse most Precent popular channels
 - ADDED the ability to import videos from twitch.tv
 - ADDED GEO blocking, user can restrict a video from being viewed from blocked locations
 - FIXED few important bugs

# Version 1.4.5 (2021)
 - ADDED New theme
 - ADDED private, public and unlisted videos
 - ADDED Custom thumbnails
 - ADDED Download button for all qualities
 - ADDED Import Facebook videos
 - ADDED URL Shortener when sharing a video link
 - ADDED Instagram username to profile
 - ADDED Age restriction
 - ADDED Donation system (Anyone can donate to channels)
 - ADDED Video timestamp on home page / featured videos
 - ADDED notifications when getting a new message in ajax mode
 - IMPROVED speed
 - FIXED few bugs

# Version 1.4.3 (2020)
 - ADDED watermark on video player
 - ADDED 1080p, 2K, and 4K support to FFMPEG
 - ADDED GDPR support, cookie frame, checkboxes and privacy policy update
 - ADDED API for delete account, create playlist, and add to playlist
 - FIXED 10+ reported bugs

# Version 1.4 (2020)
 - ADDED New theme
 - ADDED duration & channels in search page
 - REMOVED Ads on YouTube videos
 - FIXED few bugs

# Version 1.3 (2020)
 - ADDED notifications system (likes, dislikes, comments, new subscriber)
 - ADDED report video system
 - ADDED load more button to sidebar
 - ADDED the ability for video owner to delete comments on his video
 - ADDED pin comments system
 - ADDED FFMPEG system, for video conversation, and auto thumbnail detection
 - ADDED comment "by top" storing
 - ADDED drag & drop for video upload
 - ADDED night mode
 - ADDED contact us form
 - FIXED few bugs

# Version 1.2.1 (2020)
 - ADDED verification system
 - ADDED announcement system
 - ADDED mp4 links support in import video tab
 - ADDED share to Linkspreed button to watch page
 - FIXED few important bugs

# Version 1.0 (2020)
 - Initial release.
