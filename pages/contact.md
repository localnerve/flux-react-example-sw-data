# Contact

## Contact Me

I love helping people, it's what I do. If you are interested in creating an app like this or need consultation, drop me a line!

<form id="contact-form">
  <p className="contact-form-name">
    <label for="form-name">
      Name<span className="required">*</span>
    </label>
    <input id="form-name" name="form-name" title="Name" type="text" placeholder="Enter your name" required aria-required="true" />
  </p>
  <p className="contact-form-email">
    <label for="form-email">
      Email<span className="required">*</span>
    </label>
    <input id="form-email" name="form-email" title="Email" type="email" placeholder="Enter your email address" required aria-required="true" />
  </p>
  <p className="contact-form-message">
    <label for="form-message">
      Message<span class="required">*</span>
    </label>
    <textarea id="form-message" name="form-message" className="form-message" title="Message" type="textarea" placeholder="Enter your message" required  aria-required="true" />
  </p>
  <p className="form-submit">
    <input type="submit" id="contact-submit" name="contact-submit" value="Submit" />
  </p>
</form>