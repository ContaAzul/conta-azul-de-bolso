# Conta Azul de Bolso - Changelogs

Example:
```xml
<?xml version="1.0" encoding="utf-8"?>
<rss version="2.0" xmlns:sparkle="http://www.andymatuschak.org/xml-namespaces/sparkle"  xmlns:dc="http://purl.org/dc/elements/1.1/">
  <channel>
    <title>Sparkle Test App Changelog</title>
    <language>en</language>
      <item>
        <title>Version 2.0</title>
        <sparkle:version>2.0</sparkle:version>
        <description>
          <![CDATA[
            <ul>
              <li>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</li>
              <li>Suspendisse sed felis ac ante ultrices rhoncus. Etiam quis elit vel nibh placerat facilisis in id leo.</li>
              <li>Vestibulum nec tortor odio, nec malesuada libero. Cras vel convallis nunc.</li>
              <li>Suspendisse tristique massa eget velit consequat tincidunt. Praesent sodales hendrerit pretium.</li>
            </ul>
          ]]>
        </description>
        <enclosure sparkle:os="android" url="https://play.google.com/store/apps/details?id=com.sample.app" />
      </item>
  </channel>
</rss>
```