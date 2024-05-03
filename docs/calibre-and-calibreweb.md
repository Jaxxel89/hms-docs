# Calibre & Calibre Web

## Calibre & Calibre Web... What is the difference? What does each do?

### Calibre

**Calibre** is a comprehensive, free, open-source e-book management software designed to organize, store, and manage e-book collections. It is equipped with a variety of features to handle all aspects of e-book management.

#### Key Features of Calibre:
- **Library Management:** Calibre allows for sorting and grouping e-books by multiple metadata fields such as title, author, date, publisher, rating, and tags.
- **E-book Conversion:** Supports conversion between a wide array of formats, including EPUB, MOBI, PDF, and others.
- **Syncing:** Capable of transferring books to and from many e-book readers, while also converting books to different formats during the transfer.
- **E-book Viewing:** Includes an in-built viewer that supports all major e-book formats.

Calibre is primarily designed for personal use and is typically run as a standalone desktop application on personal computers.

### Calibre-web

**Calibre-web** is a web application that offers a streamlined interface for browsing, reading, and downloading eBooks from a Calibre database. It acts as a more reader-friendly interface to Calibre databases, accessible via a web browser.

#### Key Features of Calibre-web:
- **Web Interface:** Provides a user-friendly web interface for accessing the e-book library from any device with a web browser.
- **Reading in Browser:** Allows users to read books directly in the browser without the need to download them.
- **User Management:** Supports multiple users with configurable permissions, ideal for sharing with family or small groups.
- **Integration with External Services:** Integrates with online services like Google Drive, Dropbox, and mail servers for book sending.

Calibre-web is useful for remote access to an e-book collection or for sharing access among a family or small community. It requires server setup and is accessed through a web browser.

Both Calibre and Calibre-web provide robust solutions for e-book management and reading, serving different needs with some overlapping functionalities.

## Understanding Calibre: A Simple Guide

Calibre is a comprehensive e-book management software that serves as a personal library for your digital books. It's designed to help you organize, manage, and enjoy your e-book collection with ease. Below is a simple guide on how to use Calibre, its benefits, and its key features.

### How to Use Calibre

1. **Adding Books**
   - Add e-books to your Calibre library by dragging and dropping them into the Calibre window or by clicking the 'Add Books' button to select files from your computer.

2. **Organizing Books**
   - Organize your books by title, author, date, and other metadata. Utilize collections, tags, and the search feature to easily locate any book in your collection.

3. **Converting Books**
   - Convert e-books between a wide variety of formats by selecting a book and clicking on 'Convert Books'. Choose your desired output format.

4. **Syncing to Devices**
   - Connect your e-book reader to your computer. Calibre will detect it and allow you to select books to sync to your device.

5. **Reading**
   - Use the integrated e-book reader in Calibre to open and read any book directly from the application.

### Why Calibre is Good

- **Comprehensive**: Supports a vast range of e-book formats, enhancing its versatility for all e-book enthusiasts.
- **All-in-One Tool**: Manages, reads, and converts your e-books all in one place.
- **Free and Open Source**: Regularly updated by a community of developers, Calibre is free with no hidden costs.
- **Customizable**: Extend its functionality with numerous plugins for a customizable experience.

### Key Features of Calibre

- **Library Management**
   - Manage your e-book collection with detailed metadata editing and automated organization.
- **Format Conversion**
   - Convert to and from many e-book formats to resolve compatibility issues across devices.
- **Device Syncing**
   - Automatically detects connected readers and syncs books in compatible formats.
- **E-book Reader**
   - An integrated reader that supports all popular e-book formats.
- **Web Server**
   - Access your book collection via any web browser through the content server feature, allowing reading on devices with internet access.

Calibre is an essential tool for anyone who enjoys reading and collecting e-books, offering a robust solution for nearly every aspect of e-book management.

## Understanding Calibre-web: A Simple Guide

Calibre-web is a web-based application that provides a user-friendly interface for accessing and managing your Calibre e-book library from a browser. It offers a convenient way to browse, read, and manage your collection remotely. Below is a simple guide on how to use Calibre-web, its benefits, and its key features.

### How to Use Calibre-web

1. **Accessing Your Library**
   - Once installed, access Calibre-web by navigating to the server's IP address or domain name in a web browser.

2. **Browsing and Searching Books**
   - Use the web interface to browse through your e-book collection. You can search for specific books by title, author, or metadata.

3. **Reading Books**
   - Open and read books directly in your browser without the need to download them, thanks to the built-in e-book reader.

4. **Downloading Books**
   - If you prefer to read offline, Calibre-web allows you to download books in various formats supported by your e-book readers.

### Why Calibre-web is Good

- **Remote Access**: Access your e-book library from anywhere using just a web browser.
- **User-Friendly Interface**: Provides a clean and intuitive interface that simplifies the management and reading of e-books.
- **Multi-User Support**: Allows multiple users to access the library with individual settings and permissions.
- **Integration Capabilities**: Integrates with external services like Google Drive and Dropbox for backup and additional storage options.

### Key Features of Calibre-web

- **Web-Based Reader**
   - Includes a feature-rich web reader for reading e-books directly in the browser.
- **Comprehensive Search**
   - Powerful search capabilities that allow you to filter and find books based on various criteria.
- **User Management**
   - Supports creating user accounts with customizable permissions, which is perfect for sharing with others.
- **Metadata Editing**
   - Modify and update book metadata directly from the web interface to keep your library organized.
- **OPDS Support**
   - Provides OPDS feed support to access your collection with compatible e-book readers and applications.

Calibre-web transforms your Calibre e-book library into a versatile, accessible, and shareable collection, making it an excellent tool for e-book enthusiasts who value convenience and accessibility.

## Connecting to Calibre-web Using OPDS

Utilizing the Open Publication Distribution System (OPDS) allows you to access your Calibre-web library directly through compatible e-book reader apps. This guide will help you set up and connect to Calibre-web using OPDS.

### Setting Up OPDS in Calibre-web

!!! info

    **If you are just trying to connect to the library, you can skip this step. This is for setting up your own calibre-web itself.**

Ensure OPDS is enabled in your Calibre-web setup by following these steps:

1. **Enable OPDS**:
    - Log into your Calibre-web admin panel.
    - Go to the settings or configuration section.
    - Find the OPDS setting and enable it, usually by checking a box or toggling a switch.

2. **Obtain the OPDS URL**:
    - Once enabled, Calibre-web will provide an OPDS URL.
    - This URL typically looks like `http://somelibraryurlhere.net/opds` and will be used in your OPDS-compatible app.

### Connecting via OPDS from Your Device

To connect to your Calibre-web library using OPDS, do the following:

1. **Select an OPDS-Compatible App**:
    - Download an e-book reader that supports OPDS, such as FBReader, Aldiko, or Moon+ Reader for Android, and Marvin for iOS.

2. **Configure the OPDS Feed**:
    - Open the e-book reader app.
    - Locate the section for adding or configuring catalogs or libraries.
    - Enter the OPDS URL from Calibre-web. You may also need to provide login credentials if your library requires authentication.

3. **Access Your Library**:
    - With the OPDS catalog added, you should be able to browse and download books directly from your Calibre-web library.

### Tips for a Smooth OPDS Experience

- **Network Accessibility**: Ensure your device can reach the server where Calibre-web is hosted. For internet access, proper port forwarding and security settings are needed.
- **Secure Connections**: Use HTTPS for your OPDS feed to secure data transmission, especially over public networks.
- **App Compatibility**: Confirm that your e-book reader app supports the OPDS version provided by Calibre-web.

By integrating OPDS with Calibre-web, you can enhance the accessibility of your e-book collection across multiple devices, making your reading experience more flexible and convenient.

## Popular OPDS-Compatible E-Book Reader Apps

Here's a list of e-book reader apps that support OPDS, organized by platform:

### Android
- **FBReader** - Supports a wide range of formats and integrates with external dictionaries.
- **Moon+ Reader** - Offers a smooth scroll and numerous features, including support for online ebook libraries and personal Calibre ebook servers.
- **Aldiko** - Features an intuitive interface and supports Adobe DRM encrypted eBooks.
- **PocketBook Reader** - Supports multiple formats and integrates with cloud storage for a comfortable reading experience.

### iOS
- **Marvin** - An advanced e-book reader for iPad and iPhone with extensive customization options and syncing capabilities.
- **KyBook** - Supports a wide range of reading formats, offers comprehensive library management, and direct access to network libraries.
- **MapleRead** - Known for its powerful features catering to avid readers and professionals.

### Windows
- **Freda** - Reads ePub (DRM-free), FB2, HTML, and TXT formats, and connects to online catalogs including OPDS.
- **Calibre** - Primarily an e-book management software with reading capabilities, it accesses OPDS catalogs through plugins.

### Multi-Platform
- **Calibre Companion** - Mainly an organizer that connects to Calibre’s content server or cloud services, and works well with other reading apps to enhance your reading experience.

These apps are ideal for accessing a wide range of e-book formats and online libraries, making it convenient to download and read books directly on your device.
