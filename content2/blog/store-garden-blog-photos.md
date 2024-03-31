---
title: Where to store your garden blog photos
date: 2018-12-11T12:09:29Z
description: One for you gdnbloggers – after a recent fracas with Flickr, a quick of summary of where online you can catalogue, store & link to your garden photos
tags: 
- gdnbloggers
- Flickr
- WordPress
- Cloudinary
images: 
- https://res.cloudinary.com/growdigital/image/upload/v1544530290/cloudinary-1544530290.png
imageAlt: 
- Screenshot of online photo catalog interface
imageCap:
- The Cloudinary Media Library interface
draft: false
---

Back in the day, I used [WordPress](https://wordpress.org) to write my blog and moreover used it to upload all my worthy garden photos. The main reason for this was the Android phone [WordPress app](https://play.google.com/store/apps/details?id=org.wordpress.android&hl=en_US), which made uploading images a breeze. Then I switched to an iPhone and that version of the app didn’t really cut the mustard. So, I switched to [Flickr](https://www.flickr.com) to manage my photos online.

Fast forward to November 2018. Flickr announced they were [“changing” Flickr free accounts](http://blog.flickr.net/en/2018/11/01/changing-flickr-free-accounts-1000-photos/). In other words, restricting the service so that you’ll have to pay if you have over 1,000 photos. In the 3 years of photographing Forest Garden Wales, I have over 2,000 photos. I’m not averse to paying money ([£4 per month](https://www.flickr.com/account/upgrade/pro)) but I don’t appreciate having the rug pulled from under my feet, as I’d invested so much time in my Flickr set up. Well, never trust a corporation.

Time to find a new home.

I tried [Postimage](https://postimages.org) for a while, a free image hosting service. But there’s no real way to catalogue your photos and I wasn’t too happy about entrusting my photo collection to a free service. Via [Netlify](https://www.netlify.com) I heard about [Cloudinary](https://cloudinary.com), a paid-for image & video platform with a free tier. The very cool thing is that, like Flickr, you can host full resolution images yet link to lower resolution images on your website. Unlike Flickr, it is _designed_ to host images for your website.

So, I’ve painstakingly moved 300+ photos from Flickr to Cloudinary, which took hours. But the good news is that I’ll be on the free tier for at least a year (with 10GB+ of storage), and then there’s a new credit-based pricing system which will keep it affordable longer term.

Here’s a handy comparison table:

<table class="display-table">
  <thead>
    <tr>
      <th>Service</th>
      <th>Pros</th>
      <th>Cons</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <th><a href="https://www.flickr.com/">Flickr</a></th>
      <td>
        <ul>
          <li>Not bad web interface for organising photos</li>
          <li><a href="https://www.flickr.com/tools/">Nice mobile app</a>, easy to upload photos</li>
        <ul>
      </td>
      <td>
        <ul>
          <li>Not really designed for hosting images, so bit fiddly</li>
          <li>Limit of 1,000 photos</li> 
          <li>£4 per month for pro account</li>
          <li>Cost me days of my life migrating photos</li>
        </ul>
      </td>
    </tr>
    <tr>
      <th><a href="https://www.wordpress.org/">WordPress</a></th>
      <td>
        <ul>
          <li>Nice web interface</li>
          <li>Really good <a href="https://wordpress.org/mobile/">mobile app</a> (tho was limited on iOS)</li>
          <li>Well supported platform</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Not designed per se for organising images, can be frustrating</li>
          <li>Requires self-hosting, which can be time consuming &/or expensive</li>
          <li>Mobile app was limited on iPhone for uploading images directly</li>
        </ul>        
      </td>
    </tr>
    <tr>
      <th><a href="https://postimages.org">Postimage</a></th>
      <td>
        <ul>
          <li>Free!</li>
          <li>Designed for hosting images, which you link to from your website</li>
          <li>Lightweight</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Free! Has been here for years but how sustainable?</li>
          <li>Good for quick hosting of images, not really designed for managing catalogues of images</li>
          <li>No facility to link to different resolution images</li>
        </ul>        
      </td>
    </tr>
    <tr>
      <th><a href="https://cloudinary.com">Cloudinary</a></th>
      <td>
        <ul>
          <li>Designed for hosting images</li>
          <li>Decent web interface, with organising tools</li>
          <li>Free tier, up to 10GB (about 200-300 hi-res photos)</li>
          <li>Very easy to create different resolution images</li>
        </ul>
      </td>
      <td>
        <ul>
          <li>Organising tools not as polished as Flickr</li>
          <li>Fairly technical</li>
          <li>No mobile app, though web upload easy from mobile</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
