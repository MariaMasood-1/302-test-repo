# 302-test-repo
@import url(http://fonts.googleapis.com/css?family=Source+Code+Pro);

body {
  background: #eee;
}
.logo {
  -webkit-animation-play-state: running !important;
  animation-play-state: running !important;
  font: bolder 4em 'Source Code Pro', sans-serif;
  letter-spacing: -0.12em;
  color: #ddd;
  animation: shadow 2s linear infinite;
  text-shadow: 1px 1px 3px grey, 2px 2px 4px lightgrey, 3px 3px 5px #aaa, 4px 4px 6px #aaa, 5px 5px 6px #bbb, 6px 6px 7px #ccc, 7px 7px 8px #ddd, 8px 8px 9px #eee;
}
@keyframes shadow {
  to {
    text-shadow: 8px 8px 9px #eee, 7px 7px 8px #ddd, 6px 6px 7px #ccc, 5px 5px 6px #bbb, 4px 4px 6px #aaa, 3px 3px 5px #aaa, 2px 2px 4px lightgrey, 1px 1px 3px grey;
    color: grey;
  }
}

