//echo "Hello Aniket"
import groovy.json.JsonSlurperClassic

node{
    def json = readFile(file:'message2.json')
    def data = new JsonSlurperClassic().parseText(json)
    echo "color: ${data.attachments[0].color}"
}
