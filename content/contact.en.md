+++
date = "2017-03-02T11:59:27-05:00"
title = "Contact"
weight = 40
draft = false

+++

<form method="post" action="mailto:spokorski@gmail.com">
    <div class="field half first">
        <label for="name">Name</label>
        <input type="text" name="name" id="name" />
    </div>
    <div class="field half">
        <label for="email">Email</label>
        <input type="text" name="email" id="email" />
    </div>
    <div class="field">
        <label for="message">Message</label>
        <textarea name="message" id="message" rows="4"  style="resize: none;"></textarea>
    </div>
    <ul class="actions">
        <li><input type="submit" value="Send to" class="special" /></li>
        <li><input type="reset" value="Reset" /></li>
    </ul>
</form>

{{< socialLinks >}}
