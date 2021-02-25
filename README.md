# 302-test-repo
import customFonts from 'custom-fonts-in-emails';
import path from 'path';

const options = {
  text: 'Make something people want',
  fontNameOrPath: 'GoudyBookletter1911',
  fontColor: 'white',
  backgroundColor: '#ff6600',
  fontSize: 40
};

customFonts.png2x(options)
  .then(console.log)
  .catch(console.error);
