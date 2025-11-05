---
layout: default
title: "Sposiv - Your Private Place Saver"
description: "Save and organize your favorite places privately on your device"
app_name: "Sposiv"
app_price: "Free"
app_description: "Save and organize your favorite places privately on your device"
app_icon: "/assets/sposiv/appicon.png"
ios_app_id: ""
appstore_link: ""
enable_smart_app_banner: true

# Sposiv's Key Features
features:
  - title: Privacy First
    description: All your location data stays on your device. No servers, no tracking, no data collection.
    fontawesome_icon_name: shield-alt

  - title: Save Any Place
    description: Quickly save locations from maps, or add places from other apps using the share extension.
    fontawesome_icon_name: map-marker-alt

  - title: Organize Your Way
    description: Create custom categories, add notes and links, and organize your spots however you like.
    fontawesome_icon_name: folder-open

  - title: Share Extension
    description: Found a great place on Instagram or TikTok? Save it instantly with our share extension.
    fontawesome_icon_name: share-alt
---

<div class="app-hero">
    <div class="container">
        <div class="app-hero-content">
            <img src="{{ page.app_icon }}" alt="{{ page.app_name }} Icon" class="hero-app-icon">
            <h1>{{ page.app_name }}</h1>
            <p class="hero-subtitle">{{ page.app_description }}</p>
            <div class="hero-buttons">
                {% if page.appstore_link %}
                <a href="{{ page.appstore_link }}" class="btn btn-primary">Download on App Store</a>
                {% else %}
                <a href="#" class="btn btn-disabled">Coming Soon to App Store</a>
                {% endif %}
                <a href="/sposiv/privacy/" class="btn btn-outline">Privacy Policy</a>
            </div>
        </div>
        <div class="app-hero-preview">
            <img src="/assets/sposiv/screenshot.png" alt="{{ page.app_name }} Screenshots" class="hero-screenshot">
        </div>
    </div>
</div>

{% include features.html %}

<section class="app-details">
    <div class="container">
        <h2>About Sposiv</h2>
        <p>Sposiv is designed for people who love discovering new places but want to keep their location data private. Whether you're saving a restaurant recommendation from Instagram, bookmarking a hiking trail from TikTok, or organizing your favorite coffee shops, Sposiv keeps everything on your device.</p>
        
        <div class="privacy-highlight">
            <h3>🔒 Your Privacy Matters</h3>
            <p>Unlike other apps, Sposiv doesn't send your location data to servers. Everything stays on your iPhone, giving you complete control over your personal information.</p>
        </div>

        <h3>Perfect For:</h3>
        <ul>
            <li>Travel planning and recommendations</li>
            <li>Organizing local favorites</li>
            <li>Saving places from social media</li>
            <li>Building personal location collections</li>
        </ul>
    </div>
</section>

<section class="support-section">
    <div class="container">
        <h2>Support</h2>
        <p>Need help or have questions about Sposiv?</p>
        <p>Email us at: <a href="mailto:sposiv.support@gmail.com">sposiv.support@gmail.com</a></p>
        <p><a href="/sposiv/privacy/">Read our Privacy Policy</a></p>
    </div>
</section>
