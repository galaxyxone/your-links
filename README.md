# OpenLinks.io

## This repo is a work in progress- FYI nothing works yet

### Using IPFS public gateway, easily create personalized web-pages with user defined hyperlinks, photos, article, recipe(text), social post. Login to the app, add your links and create your own website link using IPFS. Users returned a CID and link. login and change the website and user is returned new link.

[![made-with-javascript](https://img.shields.io/badge/Made%20with-JavaScript-1f425f.svg)](https://www.javascript.com)
[![](https://img.shields.io/badge/project-IPFS-blue.svg?style=flat-square)](https://ipfs.io/)


- Users using Brave will use native IPFS. Users not on Brave, personal website loads using the IPFS Public Gateway. 

## This project is still deep in development mode- come back soon for more updates
## Program Flow

- User Loggs-In (https://openlinks.io) login basically finished

- User uses UI to create a .html page that gets added to either IPFS or Pinata(as advised on IPFS Docs, https://docs.ipfs.io/how-to/websites-on-ipfs/single-page-website/#set-up-a-domain)

- User creates IPFS website with info they want (HTML Generation page working on NOW)
  
- PIN the website (ipfs add http API)

- Users personal website is linked with either IPFS CID or IPFS gateway link (return users CID to users system) 

## Future Features

-Eventually upgrade with IPNS

-Add video support(mp4,ect)

-Ability to edit pages(either get a new link or use IPNS to keep names the same)

-Decentralized login(keep asking around and looking for best options)


https://www.saltycrane.com/blog/2020/05/how-generate-static-html-using-react-typescript-and-nodejs/


<img src="https://rawgit.com/gorangajic/react-icons/master/react-icons.svg" width="120" alt="React Icons">
