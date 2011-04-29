How to install this plugin in SketchUp:
=======================================

Download the ZIP file and unzip its contents into the SketchUp plugin directory
(usually at C:\Program Files\Google\SketchUp\Plugins\ in Windows
or on the Mac- HD (not User) /Library/Application Support/Google SketchUp [*]/SketchUp/plugins/ ...your version here [*].

Keep the folder structure as it is in the ZIP file. Make sure the file called
as_loadrubyeditor.rb ends up in the SketchUp Plugins directory.
Then re-start SketchUp and look for the new menu item in the Windows menu.
If you are updating, just overwrite the old version of this plugin.

SketchUp file structure after installation:

/SketchUp Directory/                            
      /Plugins/                              ...[lowercase /plugins/ on Mac]
            as_loadrubyeditor.rb                
            /as_plugins/                        
                   /as_rubyeditor/           
                        /codemirror/              
                        /img/                 
                        /jquery-ui/             
                        /snippets/               
                        as_rubyeditor.rb          
                        as_rubyeditor_settings.rb 
                        ui.html                  
                        ui.js                     
                        ui_p.css                  
            