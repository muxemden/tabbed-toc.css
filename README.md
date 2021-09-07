  /* Sitemap HuynhHuuNam Blog new update */
  #tabbed-toc {
    margin: 0 auto;
    background-color: #FFFFFF;
    border: 4px dashed rgb(48, 167, 229);
    -webkit-box-shadow: 0 1px 3px rgba(0, 0, 0, .4);
    -moz-box-shadow: 0 1px 3px rgba(0, 0, 0, .4);
    box-shadow: 0px 1px 10px rgba(0, 0, 0, 0.55);
    overflow: hidden;
    position: relative;
    color: #333;
  }
  #tabbed-toc .loading {
    display: block;
    padding: 5px 10px;
    font: normal bold 10px/normal Helmet, Freesans, Sans-Serif;
    color: white;
  }
  #tabbed-toc ul,
  #tabbed-toc ol,
  #tabbed-toc li {
    margin: 0 0;
    padding: 0 0;
    list-style: none;
  }
  #tabbed-toc .toc-tabs {
    width: 20%;
    float: left;
    max-height: 500px;
    overflow-y: auto;
    overflow-x: hidden;
  }
  #tabbed-toc .toc-tabs li a {
    display: block;
    font: normal bold 10px/28px Helmet, Freesans, Sans-Serif;
    height: 28px;
    overflow: hidden;
    text-overflow: ellipsis;
    color: #434B50;
    text-transform: uppercase;
    text-decoration: none;
    padding: 0 12px;
    cursor: pointer;
  }
  #tabbed-toc .toc-tabs li a:hover {
    background-color: rgba(110, 193, 255, 0.68);
    color: white;
  }
  #tabbed-toc .toc-tabs li a.active-tab {
    background-color: #6EC1FF;
    color: white;
    -webkit-box-shadow: -2px 2px 2px rgba(0, 0, 0, .5);
    -moz-box-shadow: -2px 2px 2px rgba(0, 0, 0, .5);
    box-shadow: -2px 2px 2px rgba(0, 0, 0, .5);
    position: relative;
    z-index: 5;
    margin: 0 -1px 0 0;
    /* cursor:text; */
  }
  #tabbed-toc .toc-content,
  #tabbed-toc .divider-layer {
    background-color: white;
    border-left: 2px dotted #30A7E5;
    -webkit-box-sizing: border-box;
    -moz-box-sizing: border-box;
    box-sizing: border-box;
    overflow: auto;
    max-height: 500px;
  }
  #tabbed-toc .toc-content {
    width: 80%;
  }
  #tabbed-toc .divider-layer {
    float: none;
    display: block;
    position: absolute;
    top: 0;
    left: 20%;
    bottom: 0;
    -webkit-box-shadow: 0 0 7px rgba(0, 0, 0, .7);
    -moz-box-shadow: 0 0 7px rgba(0, 0, 0, .7);
    box-shadow: 0 0 7px rgba(0, 0, 0, .7);
  }
  #tabbed-toc .panel {
    position: relative;
    z-index: 5;
    font: normal normal 10px/normal Helmet, Freesans, Sans-Serif;
  }
  #tabbed-toc .panel li a {
    display: block;
    position: relative;
    font-weight: bold;
    font-size: 14px;
    color: #434B50;
    line-height: 40px;
    height: 35px;
    padding: 0 12px;
    text-decoration: none;
    outline: none;
    overflow: hidden;
  }
  #tabbed-toc .panel li time {
    display: block;
    font-style: italic;
    font-weight: normal;
    font-size: 10px;
    color: #666;
    float: right;
  }
  #tabbed-toc .panel li .summary {
    display: block;
    padding: 10px 12px 10px;
    font-style: italic;
    border-bottom: 4px solid #275827;
    overflow: hidden;
  }
  #tabbed-toc .panel li .summary img.thumbnail {
    float: left;
    display: block;
    margin: 0 8px 0 0;
    padding: 4px 4px;
    width: 72px;
    height: 72px;
    border: 1px solid #dcdcdc;
    background-color: #fafafa;
  }
  #tabbed-toc .panel li:nth-child(even) {
    background-color: #CAE6F2;
  }
  #tabbed-toc .panel li a:hover,
  #tabbed-toc .panel li a:focus,
  #tabbed-toc .panel li a:hover time,
  #tabbed-toc .panel li.bold a {
    background-color: #333;
    color: white;
    outline: none;
  }
  #tabbed-toc .panel li.bold a:hover,
  #tabbed-toc .panel li.bold a:hover time {
    background-color: #222;
  }
  @media (max-width:700px) {
    #tabbed-toc {
      border: 2px solid #333;
    }
    #tabbed-toc .toc-tabs,
    #tabbed-toc .toc-content {
      overflow: hidden;
      width: auto;
      float: none;
      display: block;
    }
    #tabbed-toc .toc-tabs li {
      display: inline;
      float: left;
    }
    #tabbed-toc .toc-tabs li a,
    #tabbed-toc .toc-tabs li a.active-tab {
      background-color: #224C19;
      -webkit-box-shadow: 2px 0 7px rgba(0, 0, 0, .4);
      -moz-box-shadow: 2px 0 7px rgba(0, 0, 0, .4);
      box-shadow: 2px 0 7px rgba(0, 0, 0, .4);
    }
    #tabbed-toc .toc-tabs li a.active-tab {
      background-color: white;
      color: #333;
    }
    #tabbed-toc .toc-content {
      border: none;
    }
    #tabbed-toc .divider-layer,
    #tabbed-toc .panel li time {
      display: none;
    }
  }
