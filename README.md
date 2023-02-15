# heyCLI

LLM powered command line. Uses GPT-3 davinci-003 as of last update. 

Helps use shell command line without need to remeber commands or spend time searching Google and stackoverflow. Demo below.

## how to install

1. Go to your terminal and download the sh file from this repo 

```
curl -o heycli_client.sh https://raw.githubusercontent.com/HeyCLI/heyCLI/main/heycli_client.sh
```

2. Source the script, type in your terminal:  

```
source heycli_client.sh
```

3. Go grab an API token here: https://signup.heycli.com/

4. Finally, set the HEYCLI_API_KEY environment variable in your terminal: 

```
export HEYCLI_API_KEY=<token>
```
5. (Optional) setup context for HeyCLI for improved answers and suggestions. Type:

```
hey setup
```

That's it, you should be able to use the "hey" command!

## IMPORTANT: 
The setup command will upload your command history as is. We will add tooling to anonymise and clean the history from potential sensitive data in the future

## Support

Encounter any issues? please open an issue or email me at hadiazzouni@heycli.com

## Demo

![alt text](https://github.com/HeyCLI/heyCLI_client/blob/main/demo_heycli.gif)

## License
  
   copyright © 2023 HeyCLI open source project

   THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
   IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
   FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
   AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
   LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
   OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
   SOFTWARE.
