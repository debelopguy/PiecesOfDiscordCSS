<img width="512" height="464" alt="image" src="https://github.com/user-attachments/assets/8aa324f5-08f2-4d89-afe0-3c2600af758b" /><br/>
# PiecesOfDiscordCSS
A list of various cool discord pieces of css I (and you) may find useful.
there isn't going to be much at the moment, but I may add more if I feel the need to.
By the way, you may combine these for any desired effect that you want. 👍
### *NOTE: You do need a client like <img width="25" height="16" alt="image" src="https://github.com/user-attachments/assets/c7eb0cf1-6b30-4466-a245-819ef3fa7536" />**[Vencord](https://vencord.dev/)** to use these, specifically the QuickCSS option.*..
<img width="153" height="44" alt="image" src="https://github.com/user-attachments/assets/b627e40e-23ad-4ef7-873d-61182fee9bb6" />

## Hide Incoming Discord Direct Messages
<sub>*Image example:*</sub><br/>
<img width="148" height="112" alt="image" src="https://github.com/user-attachments/assets/b091595c-2acb-44b2-9028-625386d9bb85" /><br/>
<img width="16" height="16" alt="informator" src="https://github.com/user-attachments/assets/c94f20d2-0046-4a6d-8733-a85fd890dd57" />This will hide the list of incoming direct messages in the top left section of your app.<br/>
<img width="16" height="16" alt="warner" src="https://github.com/user-attachments/assets/e856a34b-b52c-44c3-be6d-30752d16635f" />This also has the side effect of *not showing the ping count from visible dm entries*, which can also be useful to make the direct message list entries less distracting.<br/>
<sub>I personally use it to stay focused and not get distracted by direct messages, all while staying on the platform.</sub><br/>
<sub>**TODO: i've heard that *conditional css* is a thing, so perhaps adding only dnd functionality for this piece of css would be nice.**</sub>
```css
[class*="stack_dbd263"] [aria-label*="Direct Messages"] {
    display: none !important;
}
```

## Hide Discord Direct Message/Group Chat Channels
<sub>*Image example:*</sub><br/>
<img width="323" height="460" alt="image" src="https://github.com/user-attachments/assets/1da14829-4ee3-4adc-b455-e22b64dd7fd9" /><br/>
<img width="16" height="16" alt="informator" src="https://github.com/user-attachments/assets/c94f20d2-0046-4a6d-8733-a85fd890dd57" />This will hide all direct message and group chat entries in your Direct Messages tab, without sacrificing buttons other buttons like Friend/Message Requests, Quests and etc.<br/>
<img width="16" height="16" alt="warner" src="https://github.com/user-attachments/assets/e856a34b-b52c-44c3-be6d-30752d16635f" />Remember that this does *not* remove the ability to navigate to (and obviously use) Direct Messages/Group Chats by other means, such as right clicking on a person or navigating to them through the Search Bar. All this does is just make it harder to do so and a lot less distracting.
<sub>Can be used for the same purpose as the piece of CSS provided above.</sub><br/>
<sub>**TODO: again, making this conditional on dnd status would be nice.**</sub>
```css
[class*="channel__972a0 dm__972a0 container_e45859"] {
    display: none !important;
}
```
