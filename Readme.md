# Ext Theming Helper

This is an application that contains a diverse set of Ext JS 6+ Components on one screen. This sample application is intended to assist a 
developer/designer to create new themes for Ext JS 6.x+. When used along with Sencha Fashion which is included in Sencha Cmd, developers can 
quickly theme/skin an application. 

The sample code for this application is Open Source under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0.html).


**Version History**

* v[1.0](https://github.com/savelee/sencha-theming-tutorial/tree/master/extthemingapp) - Created by Lee Boonstra
* Forked by Shikhir 
* v2.0 - Added Ext.Window and Ext.Msg components. Changed default theme to "Yummy Chocolate" in /src/sass/var/Application.scss file

**Author** 

* Original Author: [Lee Boonstra](https://github.com/savelee)
* Updated By: [Shikhir Singh](http://www.shikhir.com/)


**Dependencies to compile**

* [Sencha Cmd 6.x+](https://www.sencha.com/products/extjs/cmd-download/) 
* [Ext JS 6.x+](https://www.sencha.com/products/extjs/)

**Wait, I just want to see how this app looks without compiling**

Good News. You have three options! 
* Run it directly from github [here](https://rawgit.com/shikhirsingh/ExtJS-Theming-Helper-App/master/build/index.html)
* A sample binary is provided in the /build directory. Download and double click the index.html
* A screenshot are also included in the /screenshots folder


**Steps to use this application to theme along side Sencha Fashion**


1. Ensure your Sencha Cmd version is greater than 6.1.1+
2. Rename the src directory of this application to ThemeHelper and place it in your (Sencha Cmd workspace)[http://docs.sencha.com/cmd/6.x/workspaces.html] 
3. Run the following command in the directory of this application: sencha app watch --fashion
4. Load the page in your browser: http://localhost:1841/ThemeHelper
5. Make changes to the Sass files located in the sencha-workspace/ThemeHelper/sass/var directory. Start by making changes to the Application.scss file.
6. Watch the browser as the page automatically reloads! 
7. (optional) Use Sencha Inspector to make changes to the theme which will automatically save changes in the save.scss file


**Troubleshooting**

* Make sure your are placing the correct directory into your Sencha Cmd workspace. You need to put in just the src directory
* Ensure your changes aren't being overridden in the save.scss file


## Disclaimer

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING 
BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE 
AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR 
ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR 
OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR 
OTHER DEALINGS IN THE SOFTWARE.
