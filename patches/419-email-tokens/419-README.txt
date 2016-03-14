Adds https://github.com/JacksonRiver/springboard_modules/commit/57023f39273c27b329e7a915759b05b2f5952230

See https://www.assembla.com/spaces/npr-digital-services-custom-sb-dev/tickets/505
See https://www.assembla.com/spaces/npr-digital-services-custom-sb-dev/tickets/419

To Generate the patch:

    cd sites/all/modules/springboard;
    git checkout cs-288-7.x-4.x-patches;
    git diff 7.x-4.9.1 -- email_wrappers/email_wrappers.module fundraiser/modules/fundraiser_webform/fundraiser_webform.module webform_confirmations/webform_confirmations.module > patches/417-email-tokens.patch;
