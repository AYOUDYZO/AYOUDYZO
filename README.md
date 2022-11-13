
@@ -66,7 +66,9 @@
  },
  "execution": {
    "noTestsAction": "error",
    "stopOnFailure": false
    "scheduleRandom": true,
    "stopOnFailure": false,
    "timeout": 180
  }
},
{
<div class="application-main " data-commit-hovercards-enabled="" data-discussion-hovercards-enabled="" data-issue-and-pr-hovercards-enabled="">
        <div itemscope="" itemtype="http://schema.org/SoftwareSourceCode" class="">
    <main id="js-repo-pjax-container">
      
  


    
    







    <div id="repository-container-header" class="pt-3 hide-full-screen" style="background-color: var(--color-page-header-bg);" data-turbo-replace="">

      <div class="d-flex flex-wrap flex-justify-end mb-3  px-3 px-md-4 px-lg-5" style="gap: 1rem;">

        <div class="flex-auto min-width-0 width-fit mr-3">
            
  <div class=" d-flex flex-wrap flex-items-center wb-break-word f3 text-normal">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo color-fg-muted mr-2">
    <path fill-rule="evenodd" d="M2 2.5A2.5 2.5 0 014.5 0h8.75a.75.75 0 01.75.75v12.5a.75.75 0 01-.75.75h-2.5a.75.75 0 110-1.5h1.75v-2h-8a1 1 0 00-.714 1.7.75.75 0 01-1.072 1.05A2.495 2.495 0 012 11.5v-9zm10.5-1V9h-8c-.356 0-.694.074-1 .208V2.5a1 1 0 011-1h8zM5 12.25v3.25a.25.25 0 00.4.2l1.45-1.087a.25.25 0 01.3 0L8.6 15.7a.25.25 0 00.4-.2v-3.25a.25.25 0 00-.25-.25h-3.5a.25.25 0 00-.25.25z"></path>
</svg>
    
    <span class="author flex-self-stretch" itemprop="author">
      <a class="url fn" rel="author" data-hovercard-type="organization" data-hovercard-url="/orgs/tensorflow/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/tensorflow">tensorflow</a>
    </span>
    <span class="mx-1 flex-self-stretch color-fg-muted">/</span>
    <strong itemprop="name" class="mr-2 flex-self-stretch">
      <a data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" href="/tensorflow/tensorflow">tensorflow</a>
    </strong>

    <span></span><span class="Label Label--secondary v-align-middle mr-1">Public</span>
  </div>


        </div>

          <ul class="pagehead-actions flex-shrink-0 d-none d-md-inline" style="padding: 2px 0;">

      

  <li>
          <notifications-list-subscription-form data-action="notifications-dialog-label-toggled:notifications-list-subscription-form#handleDialogLabelToggle" class="f5 position-relative" data-catalyst="">
      <details class="details-reset details-overlay f5 position-relative" data-target="notifications-list-subscription-form.details" data-action="toggle:notifications-list-subscription-form#detailsToggled">

        <summary data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;WATCH_BUTTON&quot;,&quot;repository_id&quot;:45717250,&quot;originating_url&quot;:&quot;https://github.com/tensorflow/tensorflow/blob/master/LICENSE&quot;,&quot;user_id&quot;:112041011}}" data-hydro-click-hmac="e897cbf7b7f4cdbcd9e6cdc3538bcd0e25e2574208dc8ffef0e6e95234402633" data-ga-click="Repository, click Watch settings, action:blob#show" aria-label="Notification settings" data-view-component="true" class="btn-sm btn" aria-haspopup="menu" role="button">    <span data-menu-button="">
            <span hidden="" data-target="notifications-list-subscription-form.unwatchButtonCopy">
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-eye">
    <path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"></path>
</svg>
              Unwatch
            </span>
            <span hidden="" data-target="notifications-list-subscription-form.stopIgnoringButtonCopy">
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-bell-slash">
    <path fill-rule="evenodd" d="M8 1.5c-.997 0-1.895.416-2.534 1.086A.75.75 0 014.38 1.55 5 5 0 0113 5v2.373a.75.75 0 01-1.5 0V5A3.5 3.5 0 008 1.5zM4.182 4.31L1.19 2.143a.75.75 0 10-.88 1.214L3 5.305v2.642a.25.25 0 01-.042.139L1.255 10.64A1.518 1.518 0 002.518 13h11.108l1.184.857a.75.75 0 10.88-1.214l-1.375-.996a1.196 1.196 0 00-.013-.01L4.198 4.321a.733.733 0 00-.016-.011zm7.373 7.19L4.5 6.391v1.556c0 .346-.102.683-.294.97l-1.703 2.556a.018.018 0 00-.003.01.015.015 0 00.005.012.017.017 0 00.006.004l.007.001h9.037zM8 16a2 2 0 001.985-1.75c.017-.137-.097-.25-.235-.25h-3.5c-.138 0-.252.113-.235.25A2 2 0 008 16z"></path>
</svg>
              Stop ignoring
            </span>
            <span data-target="notifications-list-subscription-form.watchButtonCopy">
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-eye">
    <path fill-rule="evenodd" d="M1.679 7.932c.412-.621 1.242-1.75 2.366-2.717C5.175 4.242 6.527 3.5 8 3.5c1.473 0 2.824.742 3.955 1.715 1.124.967 1.954 2.096 2.366 2.717a.119.119 0 010 .136c-.412.621-1.242 1.75-2.366 2.717C10.825 11.758 9.473 12.5 8 12.5c-1.473 0-2.824-.742-3.955-1.715C2.92 9.818 2.09 8.69 1.679 8.068a.119.119 0 010-.136zM8 2c-1.981 0-3.67.992-4.933 2.078C1.797 5.169.88 6.423.43 7.1a1.619 1.619 0 000 1.798c.45.678 1.367 1.932 2.637 3.024C4.329 13.008 6.019 14 8 14c1.981 0 3.67-.992 4.933-2.078 1.27-1.091 2.187-2.345 2.637-3.023a1.619 1.619 0 000-1.798c-.45-.678-1.367-1.932-2.637-3.023C11.671 2.992 9.981 2 8 2zm0 8a2 2 0 100-4 2 2 0 000 4z"></path>
</svg>
              Watch
            </span>
          </span>
            <span id="repo-notifications-counter" data-target="notifications-list-subscription-form.socialCount" data-pjax-replace="true" data-turbo-replace="true" title="7,798" data-view-component="true" class="Counter">7.8k</span>
          <span class="dropdown-caret"></span>
</summary>
        <details-menu class="SelectMenu  " role="menu" data-target="notifications-list-subscription-form.menu" data-focus-trap="suspended"><span class="sentinel" tabindex="0" aria-hidden="true"></span>
          <div class="SelectMenu-modal notifications-component-menu-modal">
            <header class="SelectMenu-header">
              <h3 class="SelectMenu-title">Notifications</h3>
              <button class="SelectMenu-closeButton" type="button" aria-label="Close menu" data-action="click:notifications-list-subscription-form#closeMenu">
                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg>
              </button>
            </header>

            <div class="SelectMenu-list">
              <form data-target="notifications-list-subscription-form.form" data-action="submit:notifications-list-subscription-form#submitForm" data-turbo="false" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="wH0JanPV3B3R9JpbKNwFGncCHvqD36aBTHlFx31hTRdEagwYf1t3A2Yvz1b3mYEhGD912yka3OElSqXei-p_cg" autocomplete="off">

                <input type="hidden" name="repository_id" value="45717250">

                <button type="submit" name="do" value="included" class="SelectMenu-item flex-items-start" role="menuitemradio" aria-checked="true" data-targets="notifications-list-subscription-form.subscriptionButtons">
                  <span class="f5">
                    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check SelectMenu-icon SelectMenu-icon--check">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
                  </span>
                  <div>
                    <div class="f5 text-bold">
                      Participating and @mentions
                    </div>
                    <div class="text-small color-fg-muted text-normal pb-1">
                      Only receive notifications from this repository when participating or @mentioned.
                    </div>
                  </div>
                </button>

                <button type="submit" name="do" value="subscribed" class="SelectMenu-item flex-items-start" role="menuitemradio" aria-checked="false" data-targets="notifications-list-subscription-form.subscriptionButtons">
                  <span class="f5">
                    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check SelectMenu-icon SelectMenu-icon--check">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
                  </span>
                  <div>
                    <div class="f5 text-bold">
                      All Activity
                    </div>
                    <div class="text-small color-fg-muted text-normal pb-1">
                      Notified of all notifications on this repository.
                    </div>
                  </div>
                </button>

                <button type="submit" name="do" value="ignore" class="SelectMenu-item flex-items-start" role="menuitemradio" aria-checked="false" data-targets="notifications-list-subscription-form.subscriptionButtons">
                  <span class="f5">
                    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check SelectMenu-icon SelectMenu-icon--check">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
                  </span>
                  <div>
                    <div class="f5 text-bold">
                      Ignore
                    </div>
                    <div class="text-small color-fg-muted text-normal pb-1">
                      Never be notified.
                    </div>
                  </div>
                </button>
</form>
              <button class="SelectMenu-item flex-items-start pr-3" type="button" role="menuitemradio" data-target="notifications-list-subscription-form.customButton" data-action="click:notifications-list-subscription-form#openCustomDialog" aria-haspopup="true" aria-checked="false">
                <span class="f5">
                  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check SelectMenu-icon SelectMenu-icon--check">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
                </span>
                <div>
                  <div class="d-flex flex-items-start flex-justify-between">
                    <div class="f5 text-bold">Custom</div>
                    <div class="f5 pr-1">
                      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-arrow-right">
    <path fill-rule="evenodd" d="M8.22 2.97a.75.75 0 011.06 0l4.25 4.25a.75.75 0 010 1.06l-4.25 4.25a.75.75 0 01-1.06-1.06l2.97-2.97H3.75a.75.75 0 010-1.5h7.44L8.22 4.03a.75.75 0 010-1.06z"></path>
</svg>
                    </div>
                  </div>
                  <div class="text-small color-fg-muted text-normal pb-1">
                    Select events you want to be notified of in addition to participating and @mentions.
                  </div>
                </div>
              </button>

                <div class="px-3 py-2 d-flex color-bg-subtle flex-items-center">
                  <span class="f5">
                    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-device-mobile SelectMenu-icon SelectMenu-icon--device-mobile">
    <path fill-rule="evenodd" d="M3.75 0A1.75 1.75 0 002 1.75v12.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 14.25V1.75A1.75 1.75 0 0012.25 0h-8.5zM3.5 1.75a.25.25 0 01.25-.25h8.5a.25.25 0 01.25.25v12.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25V1.75zM8 13a1 1 0 100-2 1 1 0 000 2z"></path>
</svg>
                  </span>
                  <span classname="text-small color-fg-muted text-normal pb-1">
                    Get push notifications on <a target="_blank" rel="noopener noreferrer" href="https://apps.apple.com/app/apple-store/id1477376905?ct=watch-dropdown&amp;mt=8&amp;pt=524675">iOS</a> or <a target="_blank" rel="noopener noreferrer" href="https://play.google.com/store/apps/details?id=com.github.android&amp;referrer=utm_campaign%3Dwatch-dropdown%26utm_medium%3Dweb%26utm_source%3Dgithub">Android</a>.
                  </span>
                </div>
            </div>
          </div>
        <span class="sentinel" tabindex="0" aria-hidden="true"></span></details-menu>

        <details-dialog class="notifications-component-dialog " data-target="notifications-list-subscription-form.customDialog" aria-label="Custom dialog" hidden="" role="dialog" aria-modal="true">
          <div class="SelectMenu-modal notifications-component-dialog-modal overflow-visible">
            <form data-target="notifications-list-subscription-form.customform" data-action="submit:notifications-list-subscription-form#submitCustomForm" data-turbo="false" action="/notifications/subscribe" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="-ErgQLje_nAJh1g4X-dwxqej256ARAA1oT63QVLQhiF8XeUytFBVbr5cDTWAovT9yJ6wvyqBelXIDVdYpFu0RA" autocomplete="off">

              <input type="hidden" name="repository_id" value="45717250">

              <header class="d-sm-none SelectMenu-header pb-0 border-bottom-0 px-2 px-sm-3">
                <h1 class="f3 SelectMenu-title d-inline-flex">
                  <button class="color-bg-default border-0 px-2 py-0 m-0 Link--secondary f5" aria-label="Return to menu" type="button" data-action="click:notifications-list-subscription-form#closeCustomDialog">
                    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-arrow-left">
    <path fill-rule="evenodd" d="M7.78 12.53a.75.75 0 01-1.06 0L2.47 8.28a.75.75 0 010-1.06l4.25-4.25a.75.75 0 011.06 1.06L4.81 7h7.44a.75.75 0 010 1.5H4.81l2.97 2.97a.75.75 0 010 1.06z"></path>
</svg>
                  </button>
                  Custom
                </h1>
              </header>

              <header class="d-none d-sm-flex flex-items-start pt-1">
                <button class="border-0 px-2 pt-1 m-0 Link--secondary f5" style="background-color: transparent;" aria-label="Return to menu" type="button" data-action="click:notifications-list-subscription-form#closeCustomDialog">
                  <svg style="position: relative; left: 2px; top: 1px" aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-arrow-left">
    <path fill-rule="evenodd" d="M7.78 12.53a.75.75 0 01-1.06 0L2.47 8.28a.75.75 0 010-1.06l4.25-4.25a.75.75 0 011.06 1.06L4.81 7h7.44a.75.75 0 010 1.5H4.81l2.97 2.97a.75.75 0 010 1.06z"></path>
</svg>
                </button>

                <h1 class="pt-1 pr-4 pb-0 pl-0 f5 text-bold">
                  Custom
                </h1>
              </header>

              <fieldset>
                <legend>
                  <div class="text-small color-fg-muted pt-0 pr-3 pb-3 pl-6 pl-sm-5 border-bottom mb-3">
                    Select events you want to be notified of in addition to participating and @mentions.
                  </div>
                </legend>
                <div data-target="notifications-list-subscription-form.labelInputs">
                </div>
                  <div class="form-checkbox mr-3 ml-6 ml-sm-5 mb-2 mt-0">
                    <label class="f5 text-normal">
                      <input type="checkbox" name="thread_types[]" value="Issue" data-targets="notifications-list-subscription-form.threadTypeCheckboxes" data-action="change:notifications-list-subscription-form#threadTypeCheckboxesUpdated">
                      Issues
                    </label>


                  </div>
                  <div class="form-checkbox mr-3 ml-6 ml-sm-5 mb-2 mt-0">
                    <label class="f5 text-normal">
                      <input type="checkbox" name="thread_types[]" value="PullRequest" data-targets="notifications-list-subscription-form.threadTypeCheckboxes" data-action="change:notifications-list-subscription-form#threadTypeCheckboxesUpdated">
                      Pull requests
                    </label>


                  </div>
                  <div class="form-checkbox mr-3 ml-6 ml-sm-5 mb-2 mt-0">
                    <label class="f5 text-normal">
                      <input type="checkbox" name="thread_types[]" value="Release" data-targets="notifications-list-subscription-form.threadTypeCheckboxes" data-action="change:notifications-list-subscription-form#threadTypeCheckboxesUpdated">
                      Releases
                    </label>


                  </div>
                  <div class="form-checkbox mr-3 ml-6 ml-sm-5 mb-2 mt-0">
                    <label class="f5 text-normal">
                      <input type="checkbox" name="thread_types[]" value="Discussion" data-targets="notifications-list-subscription-form.threadTypeCheckboxes" data-action="change:notifications-list-subscription-form#threadTypeCheckboxesUpdated" aria-describedby="Discussion-disabled" aria-disabled="true">
                      Discussions
                    </label>

                      <div id="Discussion-disabled" class="color-fg-muted">
                        Discussions are not enabled for this repository
                      </div>

                  </div>
                  <div class="form-checkbox mr-3 ml-6 ml-sm-5 mb-2 mt-0">
                    <label class="f5 text-normal">
                      <input type="checkbox" name="thread_types[]" value="SecurityAlert" data-targets="notifications-list-subscription-form.threadTypeCheckboxes" data-action="change:notifications-list-subscription-form#threadTypeCheckboxesUpdated">
                      Security alerts
                    </label>


                  </div>
              </fieldset>
              <div class="pt-2 pb-3 px-3 d-flex flex-justify-start flex-row-reverse">
                  <button name="do" value="custom" data-target="notifications-list-subscription-form.customSubmit" disabled="disabled" type="submit" data-view-component="true" class="btn-primary btn-sm btn ml-2">    Apply
</button>

                  <button data-action="click:notifications-list-subscription-form#resetForm" data-close-dialog="" type="button" data-view-component="true" class="btn-sm btn">    Cancel
</button>
              </div>
</form>          </div>
        </details-dialog>


        <div class="notifications-component-dialog-overlay"></div>
      </details>
    </notifications-list-subscription-form>



  </li>

  <li>
        <div data-view-component="true" class="BtnGroup">
        <a icon="repo-forked" href="/tensorflow/tensorflow/fork" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FORK_BUTTON&quot;,&quot;repository_id&quot;:45717250,&quot;originating_url&quot;:&quot;https://github.com/tensorflow/tensorflow/blob/master/LICENSE&quot;,&quot;user_id&quot;:112041011}}" data-hydro-click-hmac="9188db6d8a678ce7042229123a3d6538fd27eb55aa6c243bda5753435fa1cccb" data-ga-click="Repository, show fork modal, action:blob#show; text:Fork" aria-label="Fork your own copy of tensorflow/tensorflow" data-view-component="true" class="btn-sm btn BtnGroup-item">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-repo-forked mr-2">
    <path fill-rule="evenodd" d="M5 3.25a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm0 2.122a2.25 2.25 0 10-1.5 0v.878A2.25 2.25 0 005.75 8.5h1.5v2.128a2.251 2.251 0 101.5 0V8.5h1.5a2.25 2.25 0 002.25-2.25v-.878a2.25 2.25 0 10-1.5 0v.878a.75.75 0 01-.75.75h-4.5A.75.75 0 015 6.25v-.878zm3.75 7.378a.75.75 0 11-1.5 0 .75.75 0 011.5 0zm3-8.75a.75.75 0 100-1.5.75.75 0 000 1.5z"></path>
</svg>Fork
          <span id="repo-network-counter" data-pjax-replace="true" data-turbo-replace="true" title="87,464" data-view-component="true" class="Counter">87.5k</span>
</a>
      <details group_item="true" id="my-forks-menu-45717250" data-view-component="true" class="details-reset details-overlay BtnGroup-parent d-inline-block position-relative">
              <summary aria-label="See your forks of this repository" data-view-component="true" class="btn-sm btn BtnGroup-item px-2 float-none" aria-haspopup="menu" role="button">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-triangle-down">
    <path d="M4.427 7.427l3.396 3.396a.25.25 0 00.354 0l3.396-3.396A.25.25 0 0011.396 7H4.604a.25.25 0 00-.177.427z"></path>
</svg>
</summary>
  <details-menu class="SelectMenu right-0" src="/tensorflow/tensorflow/my_forks_menu_content?can_fork=true" role="menu" data-focus-trap="suspended"><span class="sentinel" tabindex="0" aria-hidden="true"></span>
    <div class="SelectMenu-modal">
        <button class="SelectMenu-closeButton position-absolute right-0 m-2" type="button" aria-label="Close menu" data-toggle-for="details-5494a6">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg>
        </button>
      <div id="filter-menu-5494a6" class="d-flex flex-column flex-1 overflow-hidden">
        <div class="SelectMenu-list">

            <include-fragment class="SelectMenu-loading" aria-label="Loading">
              <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="32" height="32" viewBox="0 0 16 16" fill="none" data-view-component="true" class="anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
            </include-fragment>
        </div>
        
      </div>
    </div>
  <span class="sentinel" tabindex="0" aria-hidden="true"></span></details-menu>
</details></div>
  </li>

  <li>
        <template class="js-unstar-confirmation-dialog-template">
  <div class="Box-header">
    <h2 class="Box-title">Unstar this repository?</h2>
  </div>
  <div class="Box-body">
    <p class="mb-3">
      This will remove {{ repoNameWithOwner }} from the {{ listsWithCount }} that it's been added to.
    </p>
    <div class="form-actions">
      <form class="js-social-confirmation-form" data-turbo="false" action="{{ confirmUrl }}" accept-charset="UTF-8" method="post">
        <input type="hidden" name="authenticity_token" value="{{ confirmCsrfToken }}">
        <input type="hidden" name="confirm" value="true">
          <button data-close-dialog="true" type="submit" data-view-component="true" class="btn-danger btn width-full">    Unstar
</button>
</form>    </div>
  </div>
</template>

  <div data-view-component="true" class="js-toggler-container js-social-container starring-container d-flex">
    <div data-view-component="true" class="starred BtnGroup flex-1">
      <form class="js-social-form BtnGroup-parent flex-auto js-deferred-toggler-target" data-turbo="false" action="/tensorflow/tensorflow/unstar" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="3VWFEFtx0cL4K-YKsUsDCIeCg7XI9h-MGtqCaxMmHUtQSKLtHs0tD2Tk1V4f53udA5SbXI3rCdqfvq-cO63XfQ" autocomplete="off">
          <input type="hidden" value="7H3hlYeaCQNEnNj2h3K22UxIsuNmf764wuf54WGciqFhYMZowib1zthT66Ip3s5MyF6qCiNiqO5Hg9QWSRdAlw" data-csrf="true" class="js-confirm-csrf-token">
        <input type="hidden" name="context" value="repository">
          <button data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;UNSTAR_BUTTON&quot;,&quot;repository_id&quot;:45717250,&quot;originating_url&quot;:&quot;https://github.com/tensorflow/tensorflow/blob/master/LICENSE&quot;,&quot;user_id&quot;:112041011}}" data-hydro-click-hmac="5bba7d1bf85fcecc1fb68848280c75af8bb4683c1e7fd06a7156753ff22f9c61" data-ga-click="Repository, click unstar button, action:blob#show; text:Unstar" aria-label="Unstar this repository (169043)" type="submit" data-view-component="true" class="rounded-left-2 btn-sm btn BtnGroup-item">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star-fill starred-button-icon d-inline-block mr-2">
    <path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25z"></path>
</svg><span data-view-component="true" class="d-inline">
            Starred
</span>            <span id="repo-stars-counter-unstar" aria-label="169043 users starred this repository" data-singular-suffix="user starred this repository" data-plural-suffix="users starred this repository" data-turbo-replace="true" title="169,043" data-view-component="true" class="Counter js-social-count">169k</span>
</button></form>        <details id="details-user-list-45717250" data-view-component="true" class="details-reset details-overlay BtnGroup-parent js-user-list-menu d-inline-block position-relative">
        <summary aria-label="Add this repository to a list" data-view-component="true" class="btn-sm btn BtnGroup-item px-2 float-none" aria-haspopup="menu" role="button">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-triangle-down">
    <path d="M4.427 7.427l3.396 3.396a.25.25 0 00.354 0l3.396-3.396A.25.25 0 0011.396 7H4.604a.25.25 0 00-.177.427z"></path>
</svg>
</summary>
  <details-menu class="SelectMenu right-0" src="/tensorflow/tensorflow/lists" role="menu" data-focus-trap="suspended"><span class="sentinel" tabindex="0" aria-hidden="true"></span>
    <div class="SelectMenu-modal">
        <button class="SelectMenu-closeButton position-absolute right-0 m-2" type="button" aria-label="Close menu" data-toggle-for="details-0169da">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg>
        </button>
      <div id="filter-menu-0169da" class="d-flex flex-column flex-1 overflow-hidden">
        <div class="SelectMenu-list">

            <include-fragment class="SelectMenu-loading" aria-label="Loading">
              <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="32" height="32" viewBox="0 0 16 16" fill="none" data-view-component="true" class="anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
            </include-fragment>
        </div>
        
      </div>
    </div>
  <span class="sentinel" tabindex="0" aria-hidden="true"></span></details-menu>
</details>
</div>
    <div data-view-component="true" class="unstarred BtnGroup flex-1">
      <form class="js-social-form BtnGroup-parent flex-auto" data-turbo="false" action="/tensorflow/tensorflow/star" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="cUS4iXp2ZpEjja1IYX-S0lVYED9eeV_s9sZG1wpTclqoMtnxfhk124JOH5HaVm7A9g2Izfwhu8ayxf8CIo-Oxw" autocomplete="off">
        <input type="hidden" name="context" value="repository">
          <button data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;STAR_BUTTON&quot;,&quot;repository_id&quot;:45717250,&quot;originating_url&quot;:&quot;https://github.com/tensorflow/tensorflow/blob/master/LICENSE&quot;,&quot;user_id&quot;:112041011}}" data-hydro-click-hmac="1ad5cdaa88f4167053e116b3b5358f671f8343073cb1400fb1669482498a3afd" data-ga-click="Repository, click star button, action:blob#show; text:Star" aria-label="Star this repository (169043)" type="submit" data-view-component="true" class="js-toggler-target rounded-left-2 btn-sm btn BtnGroup-item">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-star d-inline-block mr-2">
    <path fill-rule="evenodd" d="M8 .25a.75.75 0 01.673.418l1.882 3.815 4.21.612a.75.75 0 01.416 1.279l-3.046 2.97.719 4.192a.75.75 0 01-1.088.791L8 12.347l-3.766 1.98a.75.75 0 01-1.088-.79l.72-4.194L.818 6.374a.75.75 0 01.416-1.28l4.21-.611L7.327.668A.75.75 0 018 .25zm0 2.445L6.615 5.5a.75.75 0 01-.564.41l-3.097.45 2.24 2.184a.75.75 0 01.216.664l-.528 3.084 2.769-1.456a.75.75 0 01.698 0l2.77 1.456-.53-3.084a.75.75 0 01.216-.664l2.24-2.183-3.096-.45a.75.75 0 01-.564-.41L8 2.694v.001z"></path>
</svg><span data-view-component="true" class="d-inline">
            Star
</span>            <span id="repo-stars-counter-star" aria-label="169043 users starred this repository" data-singular-suffix="user starred this repository" data-plural-suffix="users starred this repository" data-turbo-replace="true" title="169,043" data-view-component="true" class="Counter js-social-count">169k</span>
</button></form>        <details id="details-user-list-45717250" data-view-component="true" class="details-reset details-overlay BtnGroup-parent js-user-list-menu d-inline-block position-relative">
        <summary aria-label="Add this repository to a list" data-view-component="true" class="btn-sm btn BtnGroup-item px-2 float-none" aria-haspopup="menu" role="button">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-triangle-down">
    <path d="M4.427 7.427l3.396 3.396a.25.25 0 00.354 0l3.396-3.396A.25.25 0 0011.396 7H4.604a.25.25 0 00-.177.427z"></path>
</svg>
</summary>
  <details-menu class="SelectMenu right-0" src="/tensorflow/tensorflow/lists" role="menu" data-focus-trap="suspended"><span class="sentinel" tabindex="0" aria-hidden="true"></span>
    <div class="SelectMenu-modal">
        <button class="SelectMenu-closeButton position-absolute right-0 m-2" type="button" aria-label="Close menu" data-toggle-for="details-0169da">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg>
        </button>
      <div id="filter-menu-0169da" class="d-flex flex-column flex-1 overflow-hidden">
        <div class="SelectMenu-list">

            <include-fragment class="SelectMenu-loading" aria-label="Loading">
              <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="32" height="32" viewBox="0 0 16 16" fill="none" data-view-component="true" class="anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
            </include-fragment>
        </div>
        
      </div>
    </div>
  <span class="sentinel" tabindex="0" aria-hidden="true"></span></details-menu>
</details>
</div></div>
  </li>

    

</ul>

      </div>

        <div id="responsive-meta-container" data-turbo-replace="">
</div>


          <nav data-pjax="#js-repo-pjax-container" aria-label="Repository" data-view-component="true" class="js-repo-nav js-sidenav-container-pjax js-responsive-underlinenav overflow-hidden UnderlineNav px-3 px-md-4 px-lg-5">

  <ul data-view-component="true" class="UnderlineNav-body list-style-none">
      <li data-view-component="true" class="d-inline-flex">
  <a id="code-tab" href="/tensorflow/tensorflow" data-tab-item="i0code-tab" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages repo_deployments /tensorflow/tensorflow" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g c" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Code&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" aria-current="page" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item selected">
    
                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-code UnderlineNav-octicon d-none d-sm-inline">
    <path fill-rule="evenodd" d="M4.72 3.22a.75.75 0 011.06 1.06L2.06 8l3.72 3.72a.75.75 0 11-1.06 1.06L.47 8.53a.75.75 0 010-1.06l4.25-4.25zm6.56 0a.75.75 0 10-1.06 1.06L13.94 8l-3.72 3.72a.75.75 0 101.06 1.06l4.25-4.25a.75.75 0 000-1.06l-4.25-4.25z"></path>
</svg>
        <span data-content="Code">Code</span>
          <span id="code-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="Not available" data-view-component="true" class="Counter"></span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="issues-tab" href="/tensorflow/tensorflow/issues" data-tab-item="i1issues-tab" data-selected-links="repo_issues repo_labels repo_milestones /tensorflow/tensorflow/issues" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g i" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Issues&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item" style="">
    
                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-issue-opened UnderlineNav-octicon d-none d-sm-inline">
    <path d="M8 9.5a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path><path fill-rule="evenodd" d="M8 0a8 8 0 100 16A8 8 0 008 0zM1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0z"></path>
</svg>
        <span data-content="Issues">Issues</span>
          <span id="issues-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="2,109" data-view-component="true" class="Counter">2.1k</span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="pull-requests-tab" href="/tensorflow/tensorflow/pulls" data-tab-item="i2pull-requests-tab" data-selected-links="repo_pulls checks /tensorflow/tensorflow/pulls" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g p" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Pull requests&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item" style="visibility: hidden;">
    
                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-git-pull-request UnderlineNav-octicon d-none d-sm-inline">
    <path fill-rule="evenodd" d="M7.177 3.073L9.573.677A.25.25 0 0110 .854v4.792a.25.25 0 01-.427.177L7.177 3.427a.25.25 0 010-.354zM3.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122v5.256a2.251 2.251 0 11-1.5 0V5.372A2.25 2.25 0 011.5 3.25zM11 2.5h-1V4h1a1 1 0 011 1v5.628a2.251 2.251 0 101.5 0V5A2.5 2.5 0 0011 2.5zm1 10.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0zM3.75 12a.75.75 0 100 1.5.75.75 0 000-1.5z"></path>
</svg>
        <span data-content="Pull requests">Pull requests</span>
          <span id="pull-requests-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="274" data-view-component="true" class="Counter">274</span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="actions-tab" href="/tensorflow/tensorflow/actions" data-tab-item="i3actions-tab" data-selected-links="repo_actions /tensorflow/tensorflow/actions" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g a" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Actions&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item" style="visibility: hidden;">
    
                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-play UnderlineNav-octicon d-none d-sm-inline">
    <path fill-rule="evenodd" d="M1.5 8a6.5 6.5 0 1113 0 6.5 6.5 0 01-13 0zM8 0a8 8 0 100 16A8 8 0 008 0zM6.379 5.227A.25.25 0 006 5.442v5.117a.25.25 0 00.379.214l4.264-2.559a.25.25 0 000-.428L6.379 5.227z"></path>
</svg>
        <span data-content="Actions">Actions</span>
          <span id="actions-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="Not available" data-view-component="true" class="Counter"></span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="projects-tab" href="/tensorflow/tensorflow/projects" data-tab-item="i4projects-tab" data-selected-links="repo_projects new_repo_project repo_project /tensorflow/tensorflow/projects" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g b" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Projects&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item" style="visibility: hidden;">
    
                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-table UnderlineNav-octicon d-none d-sm-inline">
    <path fill-rule="evenodd" d="M0 1.75C0 .784.784 0 1.75 0h12.5C15.216 0 16 .784 16 1.75v12.5A1.75 1.75 0 0114.25 16H1.75A1.75 1.75 0 010 14.25V1.75zM1.5 6.5v7.75c0 .138.112.25.25.25H5v-8H1.5zM5 5H1.5V1.75a.25.25 0 01.25-.25H5V5zm1.5 1.5v8h7.75a.25.25 0 00.25-.25V6.5h-8zm8-1.5h-8V1.5h7.75a.25.25 0 01.25.25V5z"></path>
</svg>
        <span data-content="Projects">Projects</span>
          <span id="projects-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="1" data-view-component="true" class="Counter">1</span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="security-tab" href="/tensorflow/tensorflow/security" data-tab-item="i5security-tab" data-selected-links="security overview alerts policy token_scanning code_scanning /tensorflow/tensorflow/security" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-hotkey="g s" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Security&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item" style="visibility: hidden;">
    
                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-shield UnderlineNav-octicon d-none d-sm-inline">
    <path fill-rule="evenodd" d="M7.467.133a1.75 1.75 0 011.066 0l5.25 1.68A1.75 1.75 0 0115 3.48V7c0 1.566-.32 3.182-1.303 4.682-.983 1.498-2.585 2.813-5.032 3.855a1.7 1.7 0 01-1.33 0c-2.447-1.042-4.049-2.357-5.032-3.855C1.32 10.182 1 8.566 1 7V3.48a1.75 1.75 0 011.217-1.667l5.25-1.68zm.61 1.429a.25.25 0 00-.153 0l-5.25 1.68a.25.25 0 00-.174.238V7c0 1.358.275 2.666 1.057 3.86.784 1.194 2.121 2.34 4.366 3.297a.2.2 0 00.154 0c2.245-.956 3.582-2.104 4.366-3.298C13.225 9.666 13.5 8.36 13.5 7V3.48a.25.25 0 00-.174-.237l-5.25-1.68zM9 10.5a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.75a.75.75 0 10-1.5 0v3a.75.75 0 001.5 0v-3z"></path>
</svg>
        <span data-content="Security">Security</span>
            <span title="378" data-view-component="true" class="Counter">378</span>


    
</a></li>
      <li data-view-component="true" class="d-inline-flex">
  <a id="insights-tab" href="/tensorflow/tensorflow/pulse" data-tab-item="i6insights-tab" data-selected-links="repo_graphs repo_contributors dependency_graph dependabot_updates pulse people community /tensorflow/tensorflow/pulse" data-pjax="#repo-content-pjax-container" data-turbo-frame="repo-content-turbo-frame" data-analytics-event="{&quot;category&quot;:&quot;Underline navbar&quot;,&quot;action&quot;:&quot;Click tab&quot;,&quot;label&quot;:&quot;Insights&quot;,&quot;target&quot;:&quot;UNDERLINE_NAV.TAB&quot;}" data-view-component="true" class="UnderlineNav-item no-wrap js-responsive-underlinenav-item js-selected-navigation-item" style="visibility: hidden;">
    
                <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-graph UnderlineNav-octicon d-none d-sm-inline">
    <path fill-rule="evenodd" d="M1.5 1.75a.75.75 0 00-1.5 0v12.5c0 .414.336.75.75.75h14.5a.75.75 0 000-1.5H1.5V1.75zm14.28 2.53a.75.75 0 00-1.06-1.06L10 7.94 7.53 5.47a.75.75 0 00-1.06 0L3.22 8.72a.75.75 0 001.06 1.06L7 7.06l2.47 2.47a.75.75 0 001.06 0l5.25-5.25z"></path>
</svg>
        <span data-content="Insights">Insights</span>
          <span id="insights-repo-tab-count" data-pjax-replace="" data-turbo-replace="" title="Not available" data-view-component="true" class="Counter"></span>


    
</a></li>
</ul>
    <div style="" data-view-component="true" class="UnderlineNav-actions js-responsive-underlinenav-overflow position-absolute pr-3 pr-md-4 pr-lg-5 right-0">      <details data-view-component="true" class="details-overlay details-reset position-relative">
  <summary role="button" data-view-component="true" aria-haspopup="menu">          <div class="UnderlineNav-item mr-0 border-0">
            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-kebab-horizontal">
    <path d="M8 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zM1.5 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm13 0a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
</svg>
            <span class="sr-only">More</span>
          </div>
</summary>
  <details-menu role="menu" data-view-component="true" class="dropdown-menu dropdown-menu-sw" data-focus-trap="suspended"><span class="sentinel" tabindex="0" aria-hidden="true"></span>          <ul>
              <li data-menu-item="i0code-tab" hidden="">
                <a role="menuitem" class="js-selected-navigation-item selected dropdown-item" aria-current="page" data-selected-links="repo_source repo_downloads repo_commits repo_releases repo_tags repo_branches repo_packages repo_deployments /tensorflow/tensorflow" href="/tensorflow/tensorflow">
                  Code
</a>              </li>
              <li data-menu-item="i1issues-tab" hidden="">
                <a role="menuitem" class="js-selected-navigation-item dropdown-item" data-selected-links="repo_issues repo_labels repo_milestones /tensorflow/tensorflow/issues" href="/tensorflow/tensorflow/issues">
                  Issues
</a>              </li>
              <li data-menu-item="i2pull-requests-tab">
                <a role="menuitem" class="js-selected-navigation-item dropdown-item" data-selected-links="repo_pulls checks /tensorflow/tensorflow/pulls" href="/tensorflow/tensorflow/pulls">
                  Pull requests
</a>              </li>
              <li data-menu-item="i3actions-tab">
                <a role="menuitem" class="js-selected-navigation-item dropdown-item" data-selected-links="repo_actions /tensorflow/tensorflow/actions" href="/tensorflow/tensorflow/actions">
                  Actions
</a>              </li>
              <li data-menu-item="i4projects-tab">
                <a role="menuitem" class="js-selected-navigation-item dropdown-item" data-selected-links="repo_projects new_repo_project repo_project /tensorflow/tensorflow/projects" href="/tensorflow/tensorflow/projects">
                  Projects
</a>              </li>
              <li data-menu-item="i5security-tab">
                <a role="menuitem" class="js-selected-navigation-item dropdown-item" data-selected-links="security overview alerts policy token_scanning code_scanning /tensorflow/tensorflow/security" href="/tensorflow/tensorflow/security">
                  Security
</a>              </li>
              <li data-menu-item="i6insights-tab">
                <a role="menuitem" class="js-selected-navigation-item dropdown-item" data-selected-links="repo_graphs repo_contributors dependency_graph dependabot_updates pulse people community /tensorflow/tensorflow/pulse" href="/tensorflow/tensorflow/pulse">
                  Insights
</a>              </li>
          </ul>
<span class="sentinel" tabindex="0" aria-hidden="true"></span></details-menu>
</details></div>
</nav>



  </div>



  <turbo-frame id="repo-content-turbo-frame" target="_top" data-turbo-action="advance" class="">
      <div id="repo-content-pjax-container" class="repository-content ">
      <a href="https://github.dev/" class="d-none js-github-dev-shortcut" data-hotkey=".">Open in github.dev</a>
  <a href="https://github.dev/" class="d-none js-github-dev-new-tab-shortcut" data-hotkey="Shift+.,Shift+>,>" target="_blank">Open in a new github.dev tab</a>

    


    
      
  <div class="clearfix container-xl px-3 px-md-4 px-lg-5 mt-4">
    
    
<div data-test-selector="blob-container">
  

  



    
<a class="d-none js-permalink-shortcut" data-hotkey="y" href="/tensorflow/tensorflow/blob/dbaff50b56184643e78582f9322dd5a2060916df/LICENSE">Permalink</a>

<div class="d-flex flex-items-start flex-shrink-0 pb-3 flex-wrap flex-md-nowrap flex-justify-between flex-md-justify-start">
  
<div class="position-relative">
  <details class="js-branch-select-menu details-reset details-overlay mr-0 mb-0 " id="branch-select-menu" data-hydro-click-payload="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;REFS_SELECTOR_MENU&quot;,&quot;repository_id&quot;:45717250,&quot;originating_url&quot;:&quot;https://github.com/tensorflow/tensorflow/blob/master/LICENSE&quot;,&quot;user_id&quot;:112041011}}" data-hydro-click-hmac="dc53984d4fd1ed279dc8b6d79a1f8009b262f4e53ff57d8b42d3b9a769674bb3">
    <summary class="btn css-truncate" data-hotkey="w" title="Switch branches or tags">
      <svg text="gray" aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-git-branch">
    <path fill-rule="evenodd" d="M11.75 2.5a.75.75 0 100 1.5.75.75 0 000-1.5zm-2.25.75a2.25 2.25 0 113 2.122V6A2.5 2.5 0 0110 8.5H6a1 1 0 00-1 1v1.128a2.251 2.251 0 11-1.5 0V5.372a2.25 2.25 0 111.5 0v1.836A2.492 2.492 0 016 7h4a1 1 0 001-1v-.628A2.25 2.25 0 019.5 3.25zM4.25 12a.75.75 0 100 1.5.75.75 0 000-1.5zM3.5 3.25a.75.75 0 111.5 0 .75.75 0 01-1.5 0z"></path>
</svg>
      <span class="css-truncate-target" data-menu-button="">master</span>
      <span class="dropdown-caret"></span>
    </summary>

    
<div class="SelectMenu">
  <div class="SelectMenu-modal">
    <header class="SelectMenu-header">
      <span class="SelectMenu-title">Switch branches/tags</span>
      <button class="SelectMenu-closeButton" type="button" data-toggle-for="branch-select-menu"><svg aria-label="Close menu" aria-hidden="false" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg></button>
    </header>

    <input-demux data-action="tab-container-change:input-demux#storeInput tab-container-changed:input-demux#updateInput" data-catalyst="">
      <tab-container class="d-flex flex-column js-branches-tags-tabs" style="min-height: 0;">
        <div class="SelectMenu-filter">
          <input data-target="input-demux.source" id="context-commitish-filter-field" class="SelectMenu-input form-control" aria-owns="ref-list-branches" data-controls-ref-menu-id="ref-list-branches" autofocus="" autocomplete="off" aria-label="Filter branches/tags" placeholder="Filter branches/tags" type="text">
        </div>

        <div class="SelectMenu-tabs" role="tablist" data-target="input-demux.control">
          <button class="SelectMenu-tab" type="button" role="tab" aria-selected="true" tabindex="0">Branches</button>
          <button class="SelectMenu-tab" type="button" role="tab" aria-selected="false" tabindex="-1">Tags</button>
        </div>

        <div role="tabpanel" id="ref-list-branches" data-filter-placeholder="Filter branches/tags" tabindex="" class="d-flex flex-column flex-auto overflow-auto">
          <ref-selector type="branch" data-targets="input-demux.sinks" data-action="
              input-entered:ref-selector#inputEntered
              tab-selected:ref-selector#tabSelected
              focus-list:ref-selector#focusFirstListMember
            " query-endpoint="/tensorflow/tensorflow/refs" cache-key="v0:1668268499.7906702" current-committish="bWFzdGVy" default-branch="bWFzdGVy" name-with-owner="dGVuc29yZmxvdy90ZW5zb3JmbG93" prefetch-on-mouseover="" data-catalyst="">

            <template data-target="ref-selector.fetchFailedTemplate">
              <div class="SelectMenu-message" data-index="{{ index }}">Could not load branches</div>
            </template>

              <template data-target="ref-selector.noMatchTemplate">
    <div class="SelectMenu-message">Nothing to show</div>
</template>


            <div data-target="ref-selector.listContainer" role="menu" class="SelectMenu-list " data-turbo-frame="repo-content-turbo-frame">
              <div class="SelectMenu-loading pt-3 pb-0 overflow-hidden" aria-label="Menu is loading">
                <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="32" height="32" viewBox="0 0 16 16" fill="none" data-view-component="true" class="anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
              </div>
            </div>

              

<template data-target="ref-selector.itemTemplate">
  <a href="https://github.com/tensorflow/tensorflow/blob/{{ urlEncodedRefName }}/LICENSE" class="SelectMenu-item" role="menuitemradio" rel="nofollow" aria-checked="{{ isCurrent }}" data-index="{{ index }}">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check SelectMenu-icon SelectMenu-icon--check">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    <span class="flex-1 css-truncate css-truncate-overflow {{ isFilteringClass }}">{{ refName }}</span>
    <span hidden="{{ isNotDefault }}" class="Label Label--secondary flex-self-start">default</span>
  </a>
</template>


              <footer class="SelectMenu-footer"><a href="/tensorflow/tensorflow/branches">View all branches</a></footer>
          </ref-selector>

        </div>

        <div role="tabpanel" id="tags-menu" data-filter-placeholder="Find a tag" tabindex="" hidden="" class="d-flex flex-column flex-auto overflow-auto">
          <ref-selector type="tag" data-action="
              input-entered:ref-selector#inputEntered
              tab-selected:ref-selector#tabSelected
              focus-list:ref-selector#focusFirstListMember
            " data-targets="input-demux.sinks" query-endpoint="/tensorflow/tensorflow/refs" cache-key="v0:1668268499.7906702" current-committish="bWFzdGVy" default-branch="bWFzdGVy" name-with-owner="dGVuc29yZmxvdy90ZW5zb3JmbG93" data-catalyst="">

            <template data-target="ref-selector.fetchFailedTemplate">
              <div class="SelectMenu-message" data-index="{{ index }}">Could not load tags</div>
            </template>

            <template data-target="ref-selector.noMatchTemplate">
              <div class="SelectMenu-message" data-index="{{ index }}">Nothing to show</div>
            </template>

              

<template data-target="ref-selector.itemTemplate">
  <a href="https://github.com/tensorflow/tensorflow/blob/{{ urlEncodedRefName }}/LICENSE" class="SelectMenu-item" role="menuitemradio" rel="nofollow" aria-checked="{{ isCurrent }}" data-index="{{ index }}">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check SelectMenu-icon SelectMenu-icon--check">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
    <span class="flex-1 css-truncate css-truncate-overflow {{ isFilteringClass }}">{{ refName }}</span>
    <span hidden="{{ isNotDefault }}" class="Label Label--secondary flex-self-start">default</span>
  </a>
</template>


            <div data-target="ref-selector.listContainer" role="menu" class="SelectMenu-list" data-turbo-frame="repo-content-turbo-frame">
              <div class="SelectMenu-loading pt-3 pb-0 overflow-hidden" aria-label="Menu is loading">
                <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="32" height="32" viewBox="0 0 16 16" fill="none" data-view-component="true" class="anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
              </div>
            </div>
              <footer class="SelectMenu-footer"><a href="/tensorflow/tensorflow/tags">View all tags</a></footer>
          </ref-selector>
        </div>
      </tab-container>
    </input-demux>
  </div>
</div>

  </details>

</div>


<div class="Overlay--hidden Overlay-backdrop--center" data-modal-dialog-overlay="">
  <modal-dialog role="dialog" id="warn-tag-match-create-branch-dialog" aria-modal="true" aria-labelledby="warn-tag-match-create-branch-dialog-header" data-view-component="true" class="Overlay Overlay--width-large Overlay--height-auto Overlay--motion-scaleFade">
      <header class="Overlay-header Overlay-header--large Overlay-header--divided">
        <div class="Overlay-headerContentWrap">
          <div class="Overlay-titleWrap">
            <h1 id="warn-tag-match-create-branch-dialog-header" class="Overlay-title">Name already in use</h1>
          </div>
          <div class="Overlay-actionWrap">
            <button data-close-dialog-id="warn-tag-match-create-branch-dialog" aria-label="Close" type="button" data-view-component="true" class="close-button Overlay-closeButton"><svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg></button>
          </div>
        </div>
      </header>
    <div class="Overlay-body ">
      
          <div data-view-component="true">      A tag already exists with the provided branch name. Many Git commands accept both tag and branch names, so creating this branch may cause unexpected behavior. Are you sure you want to create this branch?
</div>

    </div>
      <footer class="Overlay-footer Overlay-footer--alignEnd">
            <button data-close-dialog-id="warn-tag-match-create-branch-dialog" type="button" data-view-component="true" class="btn">    Cancel
</button>
            <button data-submit-dialog-id="warn-tag-match-create-branch-dialog" type="button" data-view-component="true" class="btn-danger btn">    Create
</button>
      </footer>
</modal-dialog></div>


  <h2 id="blob-path" class="breadcrumb flex-auto flex-self-center min-width-0 text-normal mx-2 width-full width-md-auto flex-order-1 flex-md-order-none mt-3 mt-md-0">
    <span class="js-repo-root text-bold"><span class="js-path-segment d-inline-block wb-break-all"><a data-turbo-frame="repo-content-turbo-frame" href="/tensorflow/tensorflow"><span>tensorflow</span></a></span></span><span class="separator">/</span><strong class="final-path">LICENSE</strong>
  </h2>
    <a href="/tensorflow/tensorflow/find/master" data-pjax="" data-hotkey="t" data-view-component="true" class="btn mr-2 d-none d-md-block">    Go to file
</a>
  <details id="blob-more-options-details" data-view-component="true" class="details-overlay details-reset position-relative">
    <summary role="button" data-view-component="true" class="btn">    <svg aria-label="More options" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-kebab-horizontal">
    <path d="M8 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zM1.5 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm13 0a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
</svg>
</summary>
  <div data-view-component="true">      <ul class="dropdown-menu dropdown-menu-sw">
        <li class="d-block d-md-none">
          <a class="dropdown-item d-flex flex-items-baseline" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;FIND_FILE_BUTTON&quot;,&quot;repository_id&quot;:45717250,&quot;originating_url&quot;:&quot;https://github.com/tensorflow/tensorflow/blob/master/LICENSE&quot;,&quot;user_id&quot;:112041011}}" data-hydro-click-hmac="85ca2349ff44ace8ea93e10cba9593f2fe649bccc719e72e7ea3742079aa3de0" data-ga-click="Repository, find file, location:repo overview" data-hotkey="t" href="/tensorflow/tensorflow/find/master">
            <span class="flex-auto">Go to file</span>
            <span class="text-small color-fg-muted" aria-hidden="true">T</span>
</a>        </li>
        <li data-toggle-for="blob-more-options-details">
            <button data-toggle-for="jumpto-line-details-dialog" type="button" data-view-component="true" class="dropdown-item btn-link">    <span class="d-flex flex-items-baseline">
              <span class="flex-auto">Go to line</span>
              <span class="text-small color-fg-muted" aria-hidden="true">L</span>
            </span>
</button>        </li>
        <li class="dropdown-divider" role="none"></li>
        <li>
          <clipboard-copy data-toggle-for="blob-more-options-details" aria-label="Copy path" value="LICENSE" data-view-component="true" class="dropdown-item cursor-pointer" tabindex="0" role="button">
    
            Copy path

</clipboard-copy>        </li>
        <li>
          <clipboard-copy data-toggle-for="blob-more-options-details" aria-label="Copy permalink" value="https://github.com/tensorflow/tensorflow/blob/dbaff50b56184643e78582f9322dd5a2060916df/LICENSE" data-view-component="true" class="dropdown-item cursor-pointer" tabindex="0" role="button">
    
            <span class="d-flex flex-items-baseline">
              <span class="flex-auto">Copy permalink</span>
            </span>

</clipboard-copy>        </li>
      </ul>
</div>
</details></div>



      <div class="Box mb-3 clearfix">
  <div class="d-flex flex-column flex-md-row">
    <div class="p-3 col-md-6">
      <svg height="32" aria-hidden="true" viewBox="0 0 24 24" version="1.1" width="32" data-view-component="true" class="octicon octicon-law color-fg-default float-left mr-2">
    <path fill-rule="evenodd" d="M12.75 2.75a.75.75 0 00-1.5 0V4.5H9.276a1.75 1.75 0 00-.985.303L6.596 5.957A.25.25 0 016.455 6H2.353a.75.75 0 100 1.5H3.93L.563 15.18a.762.762 0 00.21.88c.08.064.161.125.309.221.186.121.452.278.792.433.68.311 1.662.62 2.876.62a6.919 6.919 0 002.876-.62c.34-.155.606-.312.792-.433.15-.097.23-.158.31-.223a.75.75 0 00.209-.878L5.569 7.5h.886c.351 0 .694-.106.984-.303l1.696-1.154A.25.25 0 019.275 6h1.975v14.5H6.763a.75.75 0 000 1.5h10.474a.75.75 0 000-1.5H12.75V6h1.974c.05 0 .1.015.14.043l1.697 1.154c.29.197.633.303.984.303h.886l-3.368 7.68a.75.75 0 00.23.896c.012.009 0 0 .002 0a3.154 3.154 0 00.31.206c.185.112.45.256.79.4a7.343 7.343 0 002.855.568 7.343 7.343 0 002.856-.569c.338-.143.604-.287.79-.399a3.5 3.5 0 00.31-.206.75.75 0 00.23-.896L20.07 7.5h1.578a.75.75 0 000-1.5h-4.102a.25.25 0 01-.14-.043l-1.697-1.154a1.75 1.75 0 00-.984-.303H12.75V2.75zM2.193 15.198a5.418 5.418 0 002.557.635 5.418 5.418 0 002.557-.635L4.75 9.368l-2.557 5.83zm14.51-.024c.082.04.174.083.275.126.53.223 1.305.45 2.272.45a5.846 5.846 0 002.547-.576L19.25 9.367l-2.547 5.807z"></path>
</svg>
      <p class="text-small color-fg-muted mb-0 lh-condensed-ultra">
        tensorflow/tensorflow
        is licensed under  the
      </p>
      <h3 class="mt-0 mb-2 h4">Apache License 2.0</h3>
      <p class="mb-0 color-fg-muted text-small pr-2">A permissive license whose main conditions require preservation of copyright and license notices. Contributors provide an express grant of patent rights. Licensed works, modifications, and larger works may be distributed under different terms and without source code.</p>
    </div>

    <div class="d-flex px-3 col-md-6 flex-column flex-sm-row pb-sm-3">
        <div class="pb-3 col-sm-4 pt-md-2">
          <h4 class="mt-1 mb-2 h5">Permissions</h4>
          <ul class="list-style-none">
              <li class="text-small pl-3">
                <svg width="13" class="octicon octicon-check color-fg-success ml-n3 v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
                <span class="v-align-middle" title="The licensed material and derivatives may be used for commercial purposes.">
                  Stabge 
								use 54 ret def listSum(numbers):
2	  if not numbers:
3	    return 2 to 45
4	  else:
5	    (f, rest) = numbers
6	    return f + listSum(rest)
7	
8	myList = (1, (2, (3, None)))
9	total = listSum(myList)
                </span>
              </li>
              <li class="text-small pl-3">
                <svg width="13" class="octicon octicon-check color-fg-success ml-n3 v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
                <span class="v-align-middle" title="The licensed material may be modified.">
                  Modification
                </span>
         def listSum(numbers):
2	  if not numbers:
3	    return 0
4	  else:
5	    (f, rest) = numbers
6	    return f + listSum(rest)
7	
8	myList = (+45, (2, (-45, None)))
9	total = listSum(myList)      </li>
              <li class="text-small pl-3">def listSum(numbers):
2	  if not numbers:
3	    return 2/45
4	  else:
5	    (f, rest) = numbers
6	    return f + listSum(rest)
7	
8	myList = (1, (2, (3, None)))
9	total = listSum(myList) 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
                <span class="v-align-middle" title="The licensed material may be distributed.">
                  Distribution
                </span>
              </li>
              <li class="text-small pl-3">
                <svg width="13" class="octicon octicon-check color-fg-success ml-n3 v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
                <span class="v-align-middle" title="This license provides an express grant of patent rights from contributors.">
                  Patent use
                </span>
              </li>
              <li class="text-small pl-3">
                <svg width="13" class="octicon octicon-check color-fg-success ml-n3 v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path></svg>
                <span class="v-align-middle" title="The licensed material may be used and modified in private.">
                  Private use
                </span>
              </li>
          </ul>
        </div> fg24292 e6ffg3r
        <div class="pb-3 col-sm-4 pt-md-2">
          <h4 class="mt-1 mb-2 h5">Limitations</h4>
          <ul class="list-style-none">
              <li class="text-small pl-3">
                <svg width="13" class="octicon octicon-x color-fg-danger ml-n3 v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg>
                <span class="v-align-middle" title="This license explicitly states that it does NOT grant trademark rights, even though licenses without such a statement probably do not grant any implicit trademark rights.">
                  Trademark use
                </span>
              </li> ff7gtrg rte frezkg
              <li class="text-small pl-3">
                <svg width="13" class="octicon octicon-x color-fg-danger ml-n3 ret dre 
								v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg>
                <span class="v-align-middle" title="This license includes a limitation of liability.">
                  Liability
                </span>
              </li>
              <li class="text-small pl-3">
                <svg width="13" class="octicon octicon-x color-fg-danger ml-n3 v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path></svg>
                <span class="v-align-middle" title="This license explicitly states that it does NOT provide any warranty.">
                  Warranty
                </span>
              </li>
          </ul>
        </div>
        <div class="pb-3 col-sm-4 pt-md-2">
          <h4 class="mt-1 mb-2 h5">Conditions</h4>
          <ul class="list-style-none to 45/ 54/ 2/ ret  ">
              <li class="text-small pl-3">
               ret 54 /2/ 45/2 ret frezh 
							<svg width="13" class="octicon octicon-info color-fg-accent ml-n3 v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm6.5-.25A.75.75 0 017.25 7h1a.75.75 0 01.75.75v2.75h.25a.75.75 0 010 1.5h-2a.75.75 0 010-1.5h.25v-2h-.25a.75.75 0 01-.75-.75zM8 6a1 1 0 100-2 1 1 0 000 2z"></path></svg>
                <span class="v-align-middle" title="A copy of the license and copyright notice must be included with the licensed material.">
                  License and copyright notice
									<path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v/ ret grety 54/(' to 54/00/2.5z"></path>
              <li class="text-small pl-3">
               listSum(numbers):
	  if not numbers:
    return 0 ret 54 /2 / rezf plotre 54/2 *020202542*/8250 ret 
 	  else:
	    (f, rest) = numbers
	    return f + listSum(rest)
	
	myList = (1, (2, (3, None)))
	total = listSum(myList)
							 <svg width="13" class="octicon octicon-info color-fg-accent ml-n3 v-align-middle" viewBox="0 0 16 16" version="1.1" height="13" aria-hidden="true"><path fill-rule="evenodd" d="M8 1.5a6.5 6.5 0 100 13 6.5 6.5 0 000-13zM0 8a8 8 0 1116 0A8 8 0 010 8zm6.5-.25A.75.75 0 017.25 7h1a.75.75 0 01.75.75v2.75h.25a.75.75 0 010 1.5h-2a.75.75 0 010-1.5h.25v-2h-.25a.75.75 0 01-.75-.75zM8 6a1 1 0 100-2 1 1 0 000 2z"></path></svg>
                <span class="v-align-middle" title="Changes made to the licensed material must be documented.">
                  ret no State changes cod n* 54/2 
                </span>
              </li>
          </ul>
        </div>
    </div>
  </div>
  <p class="color-fg-muted text-small mb-0 border-top col-12 float-left p-2 px-sm-3">
    This is not legal advice.
    <a href="https://docs.github.com/articles/licensing-a-repository/#disclaimer">Learn more about repository licenses</a>.
  </p>
</div>



    <div id="spoof-warning" class="mt-0 pb-3" hidden="" aria-hidden="">
  <div data-view-component="true" class="flash flash-warn mt-0 clearfix">
  
  
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert float-left mt-1">
    <path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path>
</svg>

      <div class="overflow-hidden">This commit does not belong to any branch on this repository, and may belong to a fork outside of the repository.</div>


  
</div></div>

    



    <div class="Box d-flex flex-column flex-shrink-0 mb-3">
  

  <div class="Box-header Details js-details-container">
      <div class="d-flex flex-items-center">
        <span class="flex-shrink-0 ml-n1 mr-n1 mt-n1 mb-n1">
          <a rel="contributor" data-hovercard-type="user" data-hovercard-url="/users/rjpower/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/rjpower"><img class="avatar avatar-user" src="https://avatars.githubusercontent.com/u/607207?s=48&amp;v=4" width="24" height="24" alt="@rjpower"></a>
        </span>
        <div class="flex-1 d-flex flex-items-center ml-3 min-width-0">
          <div class="css-truncate css-truncate-overflow">
            <a class="text-bold Link--primary" rel="contributor" data-hovercard-type="user" data-hovercard-url="/users/rjpower/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/rjpower">rjpower</a>

              <span class="markdown-title">
                <a data-pjax="true" title="Remove duplicate LICENSE information for third_party dependencies and add license information from ACKNOWLEDGEMENTS to main license file.

PiperOrigin-RevId: 412907476
Change-Id: I92c4e9db1083e513d69fa4ac40863de58eb2e852" class="Link--secondary" href="/tensorflow/tensorflow/commit/5cbf38a7ca90d9a5e46d5e1c0ed451325ba6b832">Remove duplicate LICENSE information for third_party dependencies and…</a>
              </span>
          </div>

            <span class="hidden-text-expander ml-1 flex-shrink-0">
              <button type="button" class="ellipsis-expander js-details-target" aria-expanded="false">…</button>
            </span>

          <span class="ml-2">
            
  <details class="commit-build-statuses details-overlay details-reset js-dropdown-details hx_dropdown-fullscreen" data-deferred-details-content-url="/tensorflow/tensorflow/commit/5cbf38a7ca90d9a5e46d5e1c0ed451325ba6b832/status-details?popover=true">
    <summary class="color-fg-danger">
      <svg aria-label="8 / 11 checks OK" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg>
    </summary>
    <div class="dropdown-menu status-checks-dropdown dropdown-menu-e overflow-hidden">
      <include-fragment class="m-4 d-flex flex-column flex-items-center">
        <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="32" height="32" viewBox="0 0 16 16" fill="none" data-view-component="true" class="anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
        <div class="color-fg-muted no-wrap">Loading status checks…</div>
      </include-fragment>
    </div>
  </details>

          </span>
        </div>
        <div class="ml-3 d-flex flex-shrink-0 flex-items-center flex-justify-end color-fg-muted no-wrap">
          <span class="d-none d-md-inline">
            <span>Latest commit</span>
            <a class="text-small text-mono Link--secondary" href="/tensorflow/tensorflow/commit/5cbf38a7ca90d9a5e46d5e1c0ed451325ba6b832" data-pjax="">5cbf38a</a>
            <span itemprop="dateModified"><relative-time datetime="2021-11-29T17:26:00Z" class="no-wrap" title="Nov 29, 2021, 6:26 PM GMT+1">Nov 29, 2021</relative-time></span>
          </span>

          <a data-pjax="" href="/tensorflow/tensorflow/commits/master/LICENSE" class="ml-3 no-wrap Link--primary no-underline">
            <svg text="gray" aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-history">
    <path fill-rule="evenodd" d="M1.643 3.143L.427 1.927A.25.25 0 000 2.104V5.75c0 .138.112.25.25.25h3.646a.25.25 0 00.177-.427L2.715 4.215a6.5 6.5 0 11-1.18 4.458.75.75 0 10-1.493.154 8.001 8.001 0 101.6-5.684zM7.75 4a.75.75 0 01.75.75v2.992l2.028.812a.75.75 0 01-.557 1.392l-2.5-1A.75.75 0 017 8.25v-3.5A.75.75 0 017.75 4z"></path>
</svg>
            <span class="d-none d-sm-inline">
              <strong>History</strong>
            </span>
          </a>
        </div>
      </div>
        <div class="Details-content--hidden ml-5 mt-2"><pre class="mt-2 f6 ws-pre-wrap">… add license information from ACKNOWLEDGEMENTS to main license file.

PiperOrigin-RevId: 412907476
Change-Id: I92c4e9db1083e513d69fa4ac40863de58eb2e852</pre></div>

  </div>

  <div class="Box-body d-flex flex-items-center flex-auto border-bottom-0 flex-wrap">
    <details class="details-reset details-overlay details-overlay-dark lh-default color-fg-default float-left mr-3" id="blob_contributors_box">
      <summary class="Link--primary" role="button">
        <svg text="gray" aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-people">
    <path fill-rule="evenodd" d="M5.5 3.5a2 2 0 100 4 2 2 0 000-4zM2 5.5a3.5 3.5 0 115.898 2.549 5.507 5.507 0 013.034 4.084.75.75 0 11-1.482.235 4.001 4.001 0 00-7.9 0 .75.75 0 01-1.482-.236A5.507 5.507 0 013.102 8.05 3.49 3.49 0 012 5.5zM11 4a.75.75 0 100 1.5 1.5 1.5 0 01.666 2.844.75.75 0 00-.416.672v.352a.75.75 0 00.574.73c1.2.289 2.162 1.2 2.522 2.372a.75.75 0 101.434-.44 5.01 5.01 0 00-2.56-3.012A3 3 0 0011 4z"></path>
</svg>
        <strong>6</strong>
        
        contributors
      </summary>
      <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast" aria-label="Users who have contributed to this file" src="/tensorflow/tensorflow/contributors-list/master/LICENSE" preload="" role="dialog" aria-modal="true">
        <div class="Box-header">
          <button class="Box-btn-octicon btn-octicon float-right" type="button" aria-label="Close dialog" data-close-dialog="">
            <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-x">
    <path fill-rule="evenodd" d="M3.72 3.72a.75.75 0 011.06 0L8 6.94l3.22-3.22a.75.75 0 111.06 1.06L9.06 8l3.22 3.22a.75.75 0 11-1.06 1.06L8 9.06l-3.22 3.22a.75.75 0 01-1.06-1.06L6.94 8 3.72 4.78a.75.75 0 010-1.06z"></path>
</svg>
          </button>
          <h3 class="Box-title">
            Users who have contributed to this file
          </h3>
        </div>
        <include-fragment>
          <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="32" height="32" viewBox="0 0 16 16" fill="none" data-view-component="true" class="my-3 mx-auto d-block anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
        </include-fragment>
      </details-dialog>
    </details>
      <span class="">
    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/rjpower/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/tensorflow/tensorflow/commits/master/LICENSE?author=rjpower">
      <img class="avatar mr-2 avatar-user" src="https://avatars.githubusercontent.com/u/607207?s=48&amp;v=4" width="24" height="24" alt="@rjpower"> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/guptarohit/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/tensorflow/tensorflow/commits/master/LICENSE?author=guptarohit">
      <img class="avatar mr-2 avatar-user" src="https://avatars.githubusercontent.com/u/7895001?s=48&amp;v=4" width="24" height="24" alt="@guptarohit"> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/keveman/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/tensorflow/tensorflow/commits/master/LICENSE?author=keveman">
      <img class="avatar mr-2 avatar-user" src="https://avatars.githubusercontent.com/u/229914?s=48&amp;v=4" width="24" height="24" alt="@keveman"> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/m1guelpf/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/tensorflow/tensorflow/commits/master/LICENSE?author=m1guelpf">
      <img class="avatar mr-2 avatar-user" src="https://avatars.githubusercontent.com/u/23558090?s=48&amp;v=4" width="24" height="24" alt="@m1guelpf"> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/tensorflower-gardener/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/tensorflow/tensorflow/commits/master/LICENSE?author=tensorflower-gardener">
      <img class="avatar mr-2 avatar-user" src="https://avatars.githubusercontent.com/u/17151892?s=48&amp;v=4" width="24" height="24" alt="@tensorflower-gardener"> 
</a>    <a class="avatar-link" data-hovercard-type="user" data-hovercard-url="/users/fishercoder1534/hovercard" data-octo-click="hovercard-link-click" data-octo-dimensions="link_type:self" href="/tensorflow/tensorflow/commits/master/LICENSE?author=fishercoder1534">
      <img class="avatar mr-2 avatar-user" src="https://avatars.githubusercontent.com/u/20746576?s=48&amp;v=4" width="24" height="24" alt="@fishercoder1534"> 
</a>
</span>

  </div>
</div>



      








  
    <div data-target="readme-toc.content" class="Box mt-3 position-relative">
      
  <div class="Box-header js-blob-header py-2 pr-2 d-flex flex-shrink-0 flex-md-row flex-items-center">


  <div class="text-mono f6 flex-auto pr-3 flex-order-2 flex-md-order-1">
      



      251 lines (205 sloc)
      <span class="file-info-divider"></span>
    13.3 KB
  </div>

  <div class="d-flex py-1 py-md-0 flex-auto flex-order-1 flex-md-order-2 flex-sm-grow-0 flex-justify-between hide-sm hide-md">
      

    <div class="BtnGroup">
        <a data-permalink-href="/tensorflow/tensorflow/raw/dbaff50b56184643e78582f9322dd5a2060916df/LICENSE" href="/tensorflow/tensorflow/raw/master/LICENSE" id="raw-url" data-view-component="true" class="js-permalink-replaceable-link btn-sm btn BtnGroup-item">    Raw
</a>          <a data-permalink-href="/tensorflow/tensorflow/blame/dbaff50b56184643e78582f9322dd5a2060916df/LICENSE" href="https://github.com/tensorflow/tensorflow/blame/master/LICENSE" data-hotkey="b" data-view-component="true" class="js-update-url-with-hash js-permalink-replaceable-link btn-sm btn BtnGroup-item">    Blame
</a>    </div>

    <div class="d-flex">
        
<div class="ml-1" data-test-selector="edit-dropdown-menu-component">
  <form class="BtnGroup-parent js-update-url-with-hash " data-turbo="false" action="https://github.com/tensorflow/tensorflow/edit/master/LICENSE" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="N1_xsVEcs5O-nMS1SU55r0LrIQ0CVXuF5qTlNTw7BZE8JxpySaTOTig9YqRCH-bjdXIfpHd3xdenYjAGfPzHLQ" autocomplete="off">
      <button title="Fork this repository and edit the file" data-hotkey="e" data-disable-with="" data-test-selector="edit-icon-button" type="submit" data-view-component="true" class="btn-sm BtnGroup-item btn">    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-pencil">
    <path fill-rule="evenodd" d="M11.013 1.427a1.75 1.75 0 012.474 0l1.086 1.086a1.75 1.75 0 010 2.474l-8.61 8.61c-.21.21-.47.364-.756.445l-3.251.93a.75.75 0 01-.927-.928l.929-3.25a1.75 1.75 0 01.445-.758l8.61-8.61zm1.414 1.06a.25.25 0 00-.354 0L10.811 3.75l1.439 1.44 1.263-1.263a.25.25 0 000-.354l-1.086-1.086zM11.189 6.25L9.75 4.81l-6.286 6.287a.25.25 0 00-.064.108l-.558 1.953 1.953-.558a.249.249 0 00.108-.064l6.286-6.286z"></path>
</svg>
</button></form>
  <details class="details-reset details-overlay select-menu BtnGroup-parent d-inline-block position-relative">
      <summary data-disable-invalid="" data-disable-with="" data-dropdown-tracking="{&quot;type&quot;:&quot;blob_edit_dropdown.more_options_click&quot;,&quot;context&quot;:{&quot;repository_id&quot;:45717250,&quot;actor_id&quot;:112041011,&quot;github_dev_enabled&quot;:true,&quot;edit_enabled&quot;:true,&quot;small_screen&quot;:false}}" aria-label="Select additional options" data-view-component="true" class="js-blob-dropdown-click select-menu-button btn-sm btn BtnGroup-item float-none px-2">
</summary>    <div class="SelectMenu right-0">
      <div class="SelectMenu-modal width-full">
        <div class="SelectMenu-list SelectMenu-list--borderless py-2">
          <form class="SelectMenu-item js-update-url-with-hash " data-turbo="false" action="https://github.com/tensorflow/tensorflow/edit/master/LICENSE" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="ir2563BCTe_VOtXpyTbYa-GR8Zzus67HWyI7tHSa5Y2BxVIoaPowMkObc_jCZ0cn1gjPNZuREJUa5O6HNF0nMQ" autocomplete="off">
              <button title="Fork this repository and edit the file" data-test-selector="edit-text-button" type="submit" data-view-component="true" class="btn-invisible btn width-full d-flex flex-justify-between color-fg-default text-normal p-0">    <div class="mr-5">Edit this file</div>
              <div class="color-fg-muted">E</div>
</button></form>
            <a aria-label="Open this file in github.dev" data-test-selector="github-dev-link" data-dropdown-tracking="{&quot;type&quot;:&quot;blob_edit_dropdown.dev_link_click&quot;,&quot;context&quot;:{&quot;repository_id&quot;:45717250,&quot;actor_id&quot;:112041011,&quot;edit_enabled&quot;:true,&quot;small_screen&quot;:false}}" href="https://github.dev/" data-view-component="true" class="SelectMenu-item js-github-dev-shortcut js-blob-dropdown-click width-full d-flex flex-justify-between color-fg-default f5 text-normal">
              <div class="mr-5 no-wrap">Open in github.dev</div>
              <div class="color-fg-muted">.</div>
</a>
            <a data-platforms="windows,mac" data-test-selector="github-desktop-link" aria-label="Open this file in GitHub Desktop" href="https://desktop.github.com" data-view-component="true" class="SelectMenu-item no-wrap js-remove-unless-platform width-full text-normal color-fg-default f5">
              Open in GitHub Desktop
</a>        </div>
      </div>
    </div>
  </details>
</div>


        
<div data-test-selector="remote-clipboard-copy">
  <remote-clipboard-copy class="d-inline-block btn-octicon" style="height: 26px" data-src="/tensorflow/tensorflow/raw/dbaff50b56184643e78582f9322dd5a2060916df/LICENSE" data-action="click:remote-clipboard-copy#remoteCopy" data-state-timeout="2000" data-catalyst="">
  

  <span data-target="remote-clipboard-copy.idle">      <span class="tooltipped tooltipped-nw cursor-pointer" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;COPY_RAW_CONTENTS_BUTTON&quot;,&quot;repository_id&quot;:45717250,&quot;originating_url&quot;:&quot;https://github.com/tensorflow/tensorflow/blob/master/LICENSE&quot;,&quot;user_id&quot;:112041011}}" data-hydro-click-hmac="7ba87aa2290357ae48b02c4e228a703789bd17df92b0d929665d25dfff56d9ac" aria-label="Copy raw contents">
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy">
    <path fill-rule="evenodd" d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 010 1.5h-1.5a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-1.5a.75.75 0 011.5 0v1.5A1.75 1.75 0 019.25 16h-7.5A1.75 1.75 0 010 14.25v-7.5z"></path><path fill-rule="evenodd" d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0114.25 11h-7.5A1.75 1.75 0 015 9.25v-7.5zm1.75-.25a.25.25 0 00-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 00.25-.25v-7.5a.25.25 0 00-.25-.25h-7.5z"></path>
</svg>
</span></span>
  <span data-target="remote-clipboard-copy.fetching" hidden="">      <svg style="box-sizing: content-box; color: var(--color-icon-primary);" width="16" height="16" viewBox="0 0 16 16" fill="none" data-view-component="true" class="anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
</span>
  <span data-target="remote-clipboard-copy.success" hidden="">      <span class="tooltipped tooltipped-nw" aria-label="Copied!">
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check color-fg-success">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
      </span>
</span>
  <span data-target="remote-clipboard-copy.error" hidden="">      <span class="tooltipped tooltipped-nw" aria-label="Something went wrong. Try again.">
        <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert color-fg-attention">
    <path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path>
</svg>
      </span>
</span>
</remote-clipboard-copy></div>


          <!-- '"` --><!-- </textarea></xmp> --><form class="inline-form" data-turbo="false" action="/tensorflow/tensorflow/delete/master/LICENSE" accept-charset="UTF-8" method="post"><input type="hidden" name="authenticity_token" value="3GwKuB_VGJwQHre9a7mOqujgAuhRfXMQokflFNGPz7oWEFNXFibH0TIKI3Hee7fgWwhHQVz-Z6vgj1QRKrWgyA">
            <button class="btn-octicon btn-octicon-danger tooltipped tooltipped-nw" type="submit" aria-label="Fork this repository and delete the file" data-disable-with="">
              <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-trash">
    <path fill-rule="evenodd" d="M6.5 1.75a.25.25 0 01.25-.25h2.5a.25.25 0 01.25.25V3h-3V1.75zm4.5 0V3h2.25a.75.75 0 010 1.5H2.75a.75.75 0 010-1.5H5V1.75C5 .784 5.784 0 6.75 0h2.5C10.216 0 11 .784 11 1.75zM4.496 6.675a.75.75 0 10-1.492.15l.66 6.6A1.75 1.75 0 005.405 15h5.19c.9 0 1.652-.681 1.741-1.576l.66-6.6a.75.75 0 00-1.492-.149l-.66 6.6a.25.25 0 01-.249.225h-5.19a.25.25 0 01-.249-.225l-.66-6.6z"></path>
</svg>
            </button>
</form>    </div>
  </div>

    <div class="d-flex hide-lg hide-xl flex-order-2 flex-grow-0">
      <details class="dropdown details-reset details-overlay d-inline-block">
        <summary class="js-blob-dropdown-click btn-octicon" aria-haspopup="true" aria-label="possible actions" data-test-selector="small-screen-more-options" data-dropdown-tracking="{&quot;type&quot;:&quot;blob_edit_dropdown.more_options_click&quot;,&quot;context&quot;:{&quot;repository_id&quot;:45717250,&quot;actor_id&quot;:112041011,&quot;github_dev_enabled&quot;:true,&quot;edit_enabled&quot;:true,&quot;small_screen&quot;:true}}">
          <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-kebab-horizontal">
    <path d="M8 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zM1.5 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm13 0a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
</svg>
        </summary>

        <ul class="dropdown-menu dropdown-menu-sw" style="width: 175px">
            <li>
                <a class="dropdown-item tooltipped tooltipped-nw js-remove-unless-platform" data-platforms="windows,mac" href="https://desktop.github.com">
                  Open with Desktop
                </a>
            </li>
          <li>
            <a class="dropdown-item" href="/tensorflow/tensorflow/raw/master/LICENSE">
              View raw
            </a>
          </li>
            <li>
              <remote-clipboard-copy class="dropdown-item" data-src="/tensorflow/tensorflow/raw/master/LICENSE" data-action="click:remote-clipboard-copy#remoteCopy" data-state-timeout="2000" data-catalyst="">
  

  <span data-target="remote-clipboard-copy.idle">                  <span class="cursor-pointer" data-hydro-click="{&quot;event_type&quot;:&quot;repository.click&quot;,&quot;payload&quot;:{&quot;target&quot;:&quot;COPY_RAW_CONTENTS_BUTTON&quot;,&quot;repository_id&quot;:45717250,&quot;originating_url&quot;:&quot;https://github.com/tensorflow/tensorflow/blob/master/LICENSE&quot;,&quot;user_id&quot;:112041011}}" data-hydro-click-hmac="7ba87aa2290357ae48b02c4e228a703789bd17df92b0d929665d25dfff56d9ac">
                    Copy raw contents
</span></span>
  <span data-target="remote-clipboard-copy.fetching" hidden="">                  Copy raw contents
                  <span class="d-inline-block position-relative" style="top: 3px">
                    <svg aria-label="fetching contents…" style="box-sizing: content-box; color: var(--color-icon-primary);" width="16" height="16" viewBox="0 0 16 16" fill="none" data-view-component="true" class="anim-rotate">
  <circle cx="8" cy="8" r="7" stroke="currentColor" stroke-opacity="0.25" stroke-width="2" vector-effect="non-scaling-stroke"></circle>
  <path d="M15 8a7.002 7.002 0 00-7-7" stroke="currentColor" stroke-width="2" stroke-linecap="round" vector-effect="non-scaling-stroke"></path>
</svg>
                  </span>
</span>
  <span data-target="remote-clipboard-copy.success" hidden="">                  Copy raw contents
                  <svg aria-label="Copied!" role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check color-fg-success">
    <path fill-rule="evenodd" d="M13.78 4.22a.75.75 0 010 1.06l-7.25 7.25a.75.75 0 01-1.06 0L2.22 9.28a.75.75 0 011.06-1.06L6 10.94l6.72-6.72a.75.75 0 011.06 0z"></path>
</svg>
</span>
  <span data-target="remote-clipboard-copy.error" hidden="">                  Copy raw contents
                  <svg aria-label="Something went wrong. Try again." role="img" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert color-fg-attention">
    <path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path>
</svg>
</span>
</remote-clipboard-copy>            </li>
            <li>
              <a class="dropdown-item" href="/tensorflow/tensorflow/blame/master/LICENSE">
                View blame
              </a>
            </li>

              <li class="dropdown-divider" role="none"></li>
              <li>
                <a class="dropdown-item" href="/tensorflow/tensorflow/edit/master/LICENSE">Edit file</a>
              </li>
                <li>
                  <a class="dropdown-item js-github-dev-shortcut js-blob-dropdown-click" data-test-selector="small-screen-github-dev-link" data-dropdown-tracking="{&quot;type&quot;:&quot;blob_edit_dropdown.dev_link_click&quot;,&quot;context&quot;:{&quot;repository_id&quot;:45717250,&quot;actor_id&quot;:112041011,&quot;edit_enabled&quot;:true,&quot;small_screen&quot;:true}}" href="https://github.dev/">Open with github.dev</a>
                </li>
              <li>
                <a class="dropdown-item menu-item-danger" href="/tensorflow/tensorflow/delete/master/LICENSE">Delete file</a>
              </li>
        </ul>
      </details>
    </div>
</div>


      
    <div itemprop="text" class="Box-body p-0 blob-wrapper data type-text  gist-border-0">

        
<div class="js-blob-code-container blob-code-content">

  <template class="js-file-alert-template">
  <div data-view-component="true" class="flash flash-warn flash-full d-flex flex-items-center">
  <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path>
</svg>
  
    <span>
      This file contains bidirectional Unicode text that may be interpreted or compiled differently than what appears below. To review, open the file in an editor that reveals hidden Unicode characters.
      <a href="https://github.co/hiddenchars" target="_blank">Learn more about bidirectional Unicode characters</a>
    </span>


  <div data-view-component="true" class="flash-action">        <a href="{{ revealButtonHref }}" data-view-component="true" class="btn-sm btn">    Show hidden characters
</a>
</div>
</div></template>
<template class="js-line-alert-template">
  <span aria-label="This line has hidden Unicode characters" data-view-component="true" class="line-alert tooltipped tooltipped-e">
    <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-alert">
    <path fill-rule="evenodd" d="M8.22 1.754a.25.25 0 00-.44 0L1.698 13.132a.25.25 0 00.22.368h12.164a.25.25 0 00.22-.368L8.22 1.754zm-1.763-.707c.659-1.234 2.427-1.234 3.086 0l6.082 11.378A1.75 1.75 0 0114.082 15H1.918a1.75 1.75 0 01-1.543-2.575L6.457 1.047zM9 11a1 1 0 11-2 0 1 1 0 012 0zm-.25-5.25a.75.75 0 00-1.5 0v2.5a.75.75 0 001.5 0v-2.5z"></path>
</svg>
</span></template>

  <table data-hpc="" class="highlight tab-size js-file-line-container js-code-nav-container js-tagsearch-file" data-tab-size="8" data-paste-markdown-skip="" data-tagsearch-lang="Text" data-tagsearch-path="LICENSE">
        <tbody><tr>
          <td id="L1" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="1"></td>
          <td id="LC1" class="blob-code blob-code-inner js-file-line">                                 Apache License</td>
        </tr>
        <tr>
          <td id="L2" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="2"></td>
          <td id="LC2" class="blob-code blob-code-inner js-file-line">                           Version 2.0, January 2004</td>
        </tr>
        <tr>
          <td id="L3" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="3"></td>
          <td id="LC3" class="blob-code blob-code-inner js-file-line">                        http.GJ
					www.apache.org/licenses/</td>
        </tr>
        <tr>
          <td id="L4" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="4"></td>
          <td id="LC4" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L5" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="5"></td>
          <td id="LC5" class="blob-code blob-code-inner js-file-line">   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION</td>
        </tr>
        <tr>
          <td id="L6" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="6"></td>
          <td id="LC6" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L7" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="7"></td>
          <td id="LC7" class="blob-code blob-code-inner js-file-line">   1. Definitions.</td>
        </tr>
        <tr>
          <td id="L8" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="8"></td>
          <td id="LC8" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L9" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="9"></td>
          <td id="LC9" class="blob-code blob-code-inner js-file-line">      "License" shall mean the terms and conditions for use, reproduction,</td>
        </tr>
        <tr>
          <td id="L10" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="10"></td>
          <td id="LC10" class="blob-code blob-code-inner js-file-line">      and distribution as defined by Sections 1 through 9 of this document.</td>
        </tr>
        <tr>
          <td id="L11" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="11"></td>
          <td id="LC11" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L12" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="12"></td>
          <td id="LC12" class="blob-code blob-code-inner js-file-line">      "Licensor" shall mean the copyright owner or entity authorized by</td>
        </tr>
        <tr>
          <td id="L13" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="13"></td>
          <td id="LC13" class="blob-code blob-code-inner js-file-line">      the copyright owner that is granting the License.</td>
        </tr>
        <tr>
          <td id="L14" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="14"></td>
          <td id="LC14" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L15" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="15"></td>
          <td id="LC15" class="blob-code blob-code-inner js-file-line">10HFY 
					Z 
					EE
					RHY 
					PO 
					"Legal Entity" shall mean the union of the acting entity and all</td>
        </tr>
        <tr>
          <td id="L16" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="16"></td>
          <td id="LC16" class="blob-code blob-code-inner js-file-line">      other entities that control, are controlled by, or are under common</td>
        </tr>
        <tr>
          <td id="L17" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="17"></td>
          <td id="LC17" class="blob-code blob-code-inner js-file-line">      control with that entity. For the purposes of this definition,</td>
        </tr>
        <tr>
          <td id="L18" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="18"></td>
          <td id="LC18" class="blob-code blob-code-inner js-file-line">      "control" means (i) the power, direct or indirect, to cause the</td>
        </tr>
        <tr>
          <td id="L19" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="19"></td>
          <td id="LC19" class="blob-code blob-code-inner js-file-line">      direction or management of such entity, whether by contract or</td>
        </tr>
        <tr>
          <td id="L20" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="20"></td>
          <td id="LC20" class="blob-code blob-code-inner js-file-line">O18Ootherwise, or (ii) ownership of fifty percent (50%) or more of the</td>
        </tr>
        <tr>
          <td id="L21" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="21"></td>
          <td id="LC21" class="blob-code blob-code-inner js-file-line">      outstanding shares, or (iii) beneficial ownership of such entity.</td>
        </tr>
        <tr>
          <td id="L22" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="22"></td>
          <td id="LC22" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L23" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="23"></td>
          <td id="LC23" class="blob-code blob-code-inner js-file-line">      "You" (or "Your") shall mean an individual or Legal Entity</td>
        </tr>
        <tr>
          <td id="L24" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="24"></td>
          <td id="LC24" class="blob-code blob-code-inner js-file-line">      exercising permissions granted by this License.</td>
        </tr>
        <tr>
          <td id="L25" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="25"></td>
          <td id="LC25" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L26" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="26"></td>
          <td id="LC26" class="blob-code blob-code-inner js-file-line">      "Source" form shall mean the preferred form for making modifications,</td>
        </tr>
        <tr>
          <td id="L27" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="27"></td>
          <td id="LC27" class="blob-code blob-code-inner js-file-line">      including but not limited to software source code, documentation</td>
        </tr>
        <tr>
          <td id="L28" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="28"></td>
          <td id="LC28" class="blob-code blob-code-inner js-file-line">      source, and configuration files.</td>
        </tr>
        <tr>
          <td id="L29" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="29"></td>
          <td id="LC29" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L30" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="30"></td>
          <td id="LC30" class="blob-code blob-code-inner js-file-line">      "Object" form shall mean any form resulting from mechanical</td>
        </tr>
        <tr>
          <td id="L31" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="31"></td>
          <td id="LC31" class="blob-code blob-code-inner js-file-line">      transformation or translation of a Source form, including but</td>
        </tr>
        <tr>
          <td id="L32" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="32"></td>
          <td id="LC32" class="blob-code blob-code-inner js-file-line">      not limited to compiled object code, generated documentation,</td>
        </tr>
        <tr>
          <td id="L33" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="33"></td>
          <td id="LC33" class="blob-code blob-code-inner js-file-line">      and conversions to other media types.</td>
        </tr>
        <tr>
          <td id="L34" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="34"></td>
          <td id="LC34" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L35" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="35"></td>
          <td id="LC35" class="blob-code blob-code-inner js-file-line">      "Work" shall mean the work of authorship, whether in Source or</td>
        </tr>
        <tr>
          <td id="L36" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="36"></td>
          <td id="LC36" class="blob-code blob-code-inner js-file-line">      Object form, made available under the License, as indicated by a</td>
        </tr>
        <tr>
          <td id="L37" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="37"></td>
          <td id="LC37" class="blob-code blob-code-inner js-file-line">      copyright notice that is included in or attached to the work</td>
        </tr>
        <tr>
          <td id="L38" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="38"></td>
          <td id="LC38" class="blob-code blob-code-inner js-file-line">      (an example is provided in the Appendix below).</td>
        </tr>
        <tr>
          <td id="L39" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="39"></td>
          <td id="LC39" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L40" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="40"></td>
          <td id="LC40" class="blob-code blob-code-inner js-file-line">      "Derivative Works" shall mean any work, whether in Source or Object</td>
        </tr>
        <tr>
          <td id="L41" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="41"></td>
          <td id="LC41" class="blob-code blob-code-inner js-file-line">      form, that is based on (or derived from) the Work and for which the</td>
        </tr>
        <tr>
          <td id="L42" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="42"></td>
          <td id="LC42" class="blob-code blob-code-inner js-file-line">      editorial revisions, annotations, elaborations, or other modifications</td>
        </tr>
        <tr>
          <td id="L43" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="43"></td>
          <td id="LC43" class="blob-code blob-code-inner js-file-line">      represent, as a whole, an original work of authorship. For the purposes</td>
        </tr>
        <tr>
          <td id="L44" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="44"></td>
          <td id="LC44" class="blob-code blob-code-inner js-file-line">      of this License, Derivative Works shall not include works that remain</td>
        </tr>
        <tr>
          <td id="L45" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="45"></td>
          <td id="LC45" class="blob-code blob-code-inner js-file-line">      separable from, or merely link (or bind by name) to the interfaces of,</td>
        </tr>
        <tr>
          <td id="L46" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="46"></td>
          <td id="LC46" class="blob-code blob-code-inner js-file-line">      the Work and Derivative Works thereof.</td>
        </tr>
        <tr>
          <td id="L47" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="47"></td>
          <td id="LC47" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L48" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="48"></td>
          <td id="LC48" class="blob-code blob-code-inner js-file-line">      "Contribution" shall mean any work of authorship, including</td>
        </tr>
        <tr>
          <td id="L49" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="49"></td>
          <td id="LC49" class="blob-code blob-code-inner js-file-line">      the original version of the Work and any modifications or additions</td>
        </tr>
        <tr>
          <td id="L50" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="50"></td>
          <td id="LC50" class="blob-code blob-code-inner js-file-line">      to that Work or Derivative Works thereof, that is intentionally</td>
        </tr>
        <tr>
          <td id="L51" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="51"></td>
          <td id="LC51" class="blob-code blob-code-inner js-file-line">      submitted to Licensor for inclusion in the Work by the copyright owner</td>
        </tr>
        <tr>
          <td id="L52" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="52"></td>
          <td id="LC52" class="blob-code blob-code-inner js-file-line">      or by an individual or Legal Entity authorized to submit on behalf of</td>
        </tr>
        <tr>
          <td id="L53" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="53"></td>
          <td id="LC53" class="blob-code blob-code-inner js-file-line">      the copyright owner. For the purposes of this definition, "submitted"</td>
        </tr>
        <tr>
          <td id="L54" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="54"></td>
          <td id="LC54" class="blob-code blob-code-inner js-file-line">      means any form of electronic, verbal, or written communication sent</td>
        </tr>
        <tr>
          <td id="L55" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="55"></td>
          <td id="LC55" class="blob-code blob-code-inner js-file-line">      to the Licensor or its representatives, including but not limited to</td>
        </tr>
        <tr>
          <td id="L56" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="56"></td>
          <td id="LC56" class="blob-code blob-code-inner js-file-line">      communication on electronic mailing lists, source code control systems,</td>
        </tr>
        <tr>
          <td id="L57" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="57"></td>
          <td id="LC57" class="blob-code blob-code-inner js-file-line">      and issue tracking systems that are managed by, or on behalf of, the</td>
        </tr>
        <tr>
          <td id="L58" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="58"></td>
          <td id="LC58" class="blob-code blob-code-inner js-file-line">      Licensor for the purpose of discussing and improving the Work, but</td>
        </tr>
        <tr>
          <td id="L59" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="59"></td>
          <td id="LC59" class="blob-code blob-code-inner js-file-line">      excluding communication that is conspicuously marked or otherwise</td>
        </tr>
        <tr>
          <td id="L60" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="60"></td>
          <td id="LC60" class="blob-code blob-code-inner js-file-line">      designated in writing by the copyright owner as "Not a Contribution."</td>
        </tr>
        <tr>
          <td id="L61" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="61"></td>
          <td id="LC61" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L62" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="62"></td>
          <td id="LC62" class="blob-code blob-code-inner js-file-line">      "Contributor" shall mean Licensor and any individual or Legal Entity</td>
        </tr>
        <tr>
          <td id="L63" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="63"></td>
          <td id="LC63" class="blob-code blob-code-inner js-file-line">      on behalf of whom a Contribution has been received by Licensor and</td>
        </tr>
        <tr>
          <td id="L64" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="64"></td>
          <td id="LC64" class="blob-code blob-code-inner js-file-line">      subsequently incorporated within the Work.</td>
        </tr>
        <tr>
          <td id="L65" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="65"></td>
          <td id="LC65" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L66" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="66"></td>
          <td id="LC66" class="blob-code blob-code-inner js-file-line">   2. Grant of Copyright License. Subject to the terms and conditions of</td>
        </tr>
        <tr>
          <td id="L67" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="67"></td>
          <td id="LC67" class="blob-code blob-code-inner js-file-line">      this License, each Contributor hereby grants to You a perpetual,</td>
        </tr>
        <tr>
          <td id="L68" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="68"></td>
          <td id="LC68" class="blob-code blob-code-inner js-file-line">      worldwide, non-exclusive, no-charge, royalty-free, irrevocable</td>
        </tr>
        <tr>
          <td id="L69" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="69"></td>
          <td id="LC69" class="blob-code blob-code-inner js-file-line">      copyright license to reproduce, prepare Derivative Works of,</td>
        </tr>
        <tr>
          <td id="L70" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="70"></td>
          <td id="LC70" class="blob-code blob-code-inner js-file-line">      publicly display, publicly perform, sublicense, and distribute the</td>
        </tr>
        <tr>
          <td id="L71" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="71"></td>
          <td id="LC71" class="blob-code blob-code-inner js-file-line">      Work and such Derivative Works in Source or Object form.</td>
        </tr>
        <tr>
          <td id="L72" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="72"></td>
          <td id="LC72" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L73" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="73"></td>
          <td id="LC73" class="blob-code blob-code-inner js-file-line">   3. Grant of Patent License. Subject to the terms and conditions of</td>
        </tr>
        <tr>
          <td id="L74" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="74"></td>
          <td id="LC74" class="blob-code blob-code-inner js-file-line">      this License, each Contributor hereby grants to You a perpetual,</td>
        </tr>
        <tr>
          <td id="L75" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="75"></td>
          <td id="LC75" class="blob-code blob-code-inner js-file-line">      worldwide, non-exclusive, no-charge, royalty-free, irrevocable</td>
        </tr>
        <tr>
          <td id="L76" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="76"></td>
          <td id="LC76" class="blob-code blob-code-inner js-file-line">      (except as stated in this section) patent license to make, have made,</td>
        </tr>
        <tr>
          <td id="L77" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="77"></td>
          <td id="LC77" class="blob-code blob-code-inner js-file-line">      use, offer to sell, sell, import, and otherwise transfer the Work,</td>
        </tr>
        <tr>
          <td id="L78" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="78"></td>
          <td id="LC78" class="blob-code blob-code-inner js-file-line">      where such license applies only to those patent claims licensable</td>
        </tr>
        <tr>
          <td id="L79" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="79"></td>
          <td id="LC79" class="blob-code blob-code-inner js-file-line">      by such Contributor that are necessarily infringed by their</td>
        </tr>
        <tr>
          <td id="L80" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="80"></td>
          <td id="LC80" class="blob-code blob-code-inner js-file-line">      Contribution(s) alone or by combination of their Contribution(s)</td>
        </tr>
        <tr>
          <td id="L81" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="81"></td>
          <td id="LC81" class="blob-code blob-code-inner js-file-line">      with the Work to which such Contribution(s) was submitted. If You</td>
        </tr>
        <tr>
          <td id="L82" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="82"></td>
          <td id="LC82" class="blob-code blob-code-inner js-file-line">      institute patent litigation against any entity (including a</td>
        </tr>
        <tr>
          <td id="L83" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="83"></td>
          <td id="LC83" class="blob-code blob-code-inner js-file-line">      cross-claim or counterclaim in a lawsuit) alleging that the Work</td>
        </tr>
        <tr>
          <td id="L84" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="84"></td>
          <td id="LC84" class="blob-code blob-code-inner js-file-line">      or a Contribution incorporated within the Work constitutes direct</td>
        </tr>
        <tr>
          <td id="L85" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="85"></td>
          <td id="LC85" class="blob-code blob-code-inner js-file-line">      or contributory patent infringement, then any patent licenses</td>
        </tr>
        <tr>
          <td id="L86" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="86"></td>
          <td id="LC86" class="blob-code blob-code-inner js-file-line">      granted to You under this License for that Work shall terminate</td>
        </tr>
        <tr>
          <td id="L87" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="87"></td>
          <td id="LC87" class="blob-code blob-code-inner js-file-line">      as of the date such litigation is filed.</td>
        </tr>
        <tr>
          <td id="L88" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="88"></td>
          <td id="LC88" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L89" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="89"></td>
          <td id="LC89" class="blob-code blob-code-inner js-file-line">   4. Redistribution. You may reproduce and distribute copies of the</td>
        </tr>
        <tr>
          <td id="L90" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="90"></td>
          <td id="LC90" class="blob-code blob-code-inner js-file-line">      Work or Derivative Works thereof in any medium, with or without</td>
        </tr>
        <tr>
          <td id="L91" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="91"></td>
          <td id="LC91" class="blob-code blob-code-inner js-file-line">      modifications, and in Source or Object form, provided that You</td>
        </tr>
        <tr>
          <td id="L92" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="92"></td>
          <td id="LC92" class="blob-code blob-code-inner js-file-line">      meet the following conditions:</td>
        </tr>
        <tr>
          <td id="L93" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="93"></td>
          <td id="LC93" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L94" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="94"></td>
          <td id="LC94" class="blob-code blob-code-inner js-file-line">      (a) You must give any other recipients of the Work or</td>
        </tr>
        <tr>
          <td id="L95" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="95"></td>
          <td id="LC95" class="blob-code blob-code-inner js-file-line">          Derivative Works a copy of this License; and</td>
        </tr>
        <tr>
          <td id="L96" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="96"></td>
          <td id="LC96" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L97" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="97"></td>
          <td id="LC97" class="blob-code blob-code-inner js-file-line">      (b) You must cause any modified files to carry prominent notices</td>
        </tr>
        <tr>
          <td id="L98" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="98"></td>
          <td id="LC98" class="blob-code blob-code-inner js-file-line">          stating that You changed the files; and</td>
        </tr>
        <tr>
          <td id="L99" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="99"></td>
          <td id="LC99" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L100" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="100"></td>
          <td id="LC100" class="blob-code blob-code-inner js-file-line">      (c) You must retain, in the Source form of any Derivative Works</td>
        </tr>
        <tr>
          <td id="L101" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="101"></td>
          <td id="LC101" class="blob-code blob-code-inner js-file-line">          that You distribute, all copyright, patent, trademark, and</td>
        </tr>
        <tr>
          <td id="L102" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="102"></td>
          <td id="LC102" class="blob-code blob-code-inner js-file-line">          attribution notices from the Source form of the Work,</td>
        </tr>
        <tr>
          <td id="L103" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="103"></td>
          <td id="LC103" class="blob-code blob-code-inner js-file-line">          excluding those notices that do not pertain to any part of</td>
        </tr>
        <tr>
          <td id="L104" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="104"></td>
          <td id="LC104" class="blob-code blob-code-inner js-file-line">          the Derivative Works; and</td>
        </tr>
        <tr>
          <td id="L105" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="105"></td>
          <td id="LC105" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L106" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="106"></td>
          <td id="LC106" class="blob-code blob-code-inner js-file-line">      (d) If the Work includes a "NOTICE" text file as part of its</td>
        </tr>
        <tr>
          <td id="L107" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="107"></td>
          <td id="LC107" class="blob-code blob-code-inner js-file-line">          distribution, then any Derivative Works that You distribute must</td>
        </tr>
        <tr>
          <td id="L108" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="108"></td>
          <td id="LC108" class="blob-code blob-code-inner js-file-line">          include a readable copy of the attribution notices contained</td>
        </tr>
        <tr>
          <td id="L109" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="109"></td>
          <td id="LC109" class="blob-code blob-code-inner js-file-line">          within such NOTICE file, excluding those notices that do not</td>
        </tr>
        <tr>
          <td id="L110" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="110"></td>
          <td id="LC110" class="blob-code blob-code-inner js-file-line">          pertain to any part of the Derivative Works, in at least one</td>
        </tr>
        <tr>
          <td id="L111" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="111"></td>
          <td id="LC111" class="blob-code blob-code-inner js-file-line">          of the following places: within a NOTICE text file distributed</td>
        </tr>
        <tr>
          <td id="L112" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="112"></td>
          <td id="LC112" class="blob-code blob-code-inner js-file-line">          as part of the Derivative Works; within the Source form or</td>
        </tr>
        <tr>
          <td id="L113" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="113"></td>
          <td id="LC113" class="blob-code blob-code-inner js-file-line">          documentation, if provided along with the Derivative Works; or,</td>
        </tr>
        <tr>
          <td id="L114" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="114"></td>
          <td id="LC114" class="blob-code blob-code-inner js-file-line">          within a display generated by the Derivative Works, if and</td>
        </tr>
        <tr>
          <td id="L115" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="115"></td>
          <td id="LC115" class="blob-code blob-code-inner js-file-line">          wherever such third-party notices normally appear. The contents</td>
        </tr>
        <tr>
          <td id="L116" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="116"></td>
          <td id="LC116" class="blob-code blob-code-inner js-file-line">          of the NOTICE file are for informational purposes only and</td>
        </tr>
        <tr>
          <td id="L117" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="117"></td>
          <td id="LC117" class="blob-code blob-code-inner js-file-line">          do not modify the License. You may add Your own attribution</td>
        </tr>
        <tr>
          <td id="L118" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="118"></td>
          <td id="LC118" class="blob-code blob-code-inner js-file-line">          notices within Derivative Works that You distribute, alongside</td>
        </tr>
        <tr>
          <td id="L119" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="119"></td>
          <td id="LC119" class="blob-code blob-code-inner js-file-line">          or as an addendum to the NOTICE text from the Work, provided</td>
        </tr>
        <tr>
          <td id="L120" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="120"></td>
          <td id="LC120" class="blob-code blob-code-inner js-file-line">          that such additional attribution notices cannot be construed</td>
        </tr>
        <tr>
          <td id="L121" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="121"></td>
          <td id="LC121" class="blob-code blob-code-inner js-file-line">          as modifying the License.</td>
        </tr>
        <tr>
          <td id="L122" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="122"></td>
          <td id="LC122" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L123" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="123"></td>
          <td id="LC123" class="blob-code blob-code-inner js-file-line">      You may add Your own copyright statement to Your modifications and</td>
        </tr>
        <tr>
          <td id="L124" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="124"></td>
          <td id="LC124" class="blob-code blob-code-inner js-file-line">      may provide additional or different license terms and conditions</td>
        </tr>
        <tr>
          <td id="L125" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="125"></td>
          <td id="LC125" class="blob-code blob-code-inner js-file-line">      for use, reproduction, or distribution of Your modifications, or</td>
        </tr>
        <tr>
          <td id="L126" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="126"></td>
          <td id="LC126" class="blob-code blob-code-inner js-file-line">      for any such Derivative Works as a whole, provided Your use,</td>
        </tr>
        <tr>
          <td id="L127" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="127"></td>
          <td id="LC127" class="blob-code blob-code-inner js-file-line">      reproduction, and distribution of the Work otherwise complies with</td>
        </tr>
        <tr>
          <td id="L128" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="128"></td>
          <td id="LC128" class="blob-code blob-code-inner js-file-line">      the conditions stated in this License.</td>
        </tr>
        <tr>
          <td id="L129" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="129"></td>
          <td id="LC129" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L130" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="130"></td>
          <td id="LC130" class="blob-code blob-code-inner js-file-line">   5. Submission of Contributions. Unless You explicitly state otherwise,</td>
        </tr>
        <tr>
          <td id="L131" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="131"></td>
          <td id="LC131" class="blob-code blob-code-inner js-file-line">      any Contribution intentionally submitted for inclusion in the Work</td>
        </tr>
        <tr>
          <td id="L132" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="132"></td>
          <td id="LC132" class="blob-code blob-code-inner js-file-line">      by You to the Licensor shall be under the terms and conditions of</td>
        </tr>
        <tr>
          <td id="L133" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="133"></td>
          <td id="LC133" class="blob-code blob-code-inner js-file-line">      this License, without any additional terms or conditions.</td>
        </tr>
        <tr>
          <td id="L134" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="134"></td>
          <td id="LC134" class="blob-code blob-code-inner js-file-line">      Notwithstanding the above, nothing herein shall supersede or modify</td>
        </tr>
        <tr>
          <td id="L135" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="135"></td>
          <td id="LC135" class="blob-code blob-code-inner js-file-line">      the terms of any separate license agreement you may have executed</td>
        </tr>
        <tr>
          <td id="L136" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="136"></td>
          <td id="LC136" class="blob-code blob-code-inner js-file-line">      with Licensor regarding such Contributions.</td>
        </tr>
        <tr>
          <td id="L137" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="137"></td>
          <td id="LC137" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L138" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="138"></td>
          <td id="LC138" class="blob-code blob-code-inner js-file-line">   6. Trademarks. This License does not grant permission to use the trade</td>
        </tr>
        <tr>
          <td id="L139" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="139"></td>
          <td id="LC139" class="blob-code blob-code-inner js-file-line">      names, trademarks, service marks, or product names of the Licensor,</td>
        </tr>
        <tr>
          <td id="L140" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="140"></td>
          <td id="LC140" class="blob-code blob-code-inner js-file-line">      except as required for reasonable and customary use in describing the</td>
        </tr>
        <tr>
          <td id="L141" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="141"></td>
          <td id="LC141" class="blob-code blob-code-inner js-file-line">      origin of the Work and reproducing the content of the NOTICE file.</td>
        </tr>
        <tr>
          <td id="L142" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="142"></td>
          <td id="LC142" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L143" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="143"></td>
          <td id="LC143" class="blob-code blob-code-inner js-file-line">   7. Disclaimer of Warranty. Unless required by applicable law or</td>
        </tr>
        <tr>
          <td id="L144" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="144"></td>
          <td id="LC144" class="blob-code blob-code-inner js-file-line">      agreed to in writing, Licensor provides the Work (and each</td>
        </tr>
        <tr>
          <td id="L145" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="145"></td>
          <td id="LC145" class="blob-code blob-code-inner js-file-line">      Contributor provides its Contributions) on an "AS IS" BASIS,</td>
        </tr>
        <tr>
          <td id="L146" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="146"></td>
          <td id="LC146" class="blob-code blob-code-inner js-file-line">      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or</td>
        </tr>
        <tr>
          <td id="L147" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="147"></td>
          <td id="LC147" class="blob-code blob-code-inner js-file-line">      implied, including, without limitation, any warranties or conditions</td>
        </tr>
        <tr>
          <td id="L148" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="148"></td>
          <td id="LC148" class="blob-code blob-code-inner js-file-line">      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A</td>
        </tr>
        <tr>
          <td id="L149" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="149"></td>
          <td id="LC149" class="blob-code blob-code-inner js-file-line">      PARTICULAR PURPOSE. You are solely responsible for determining the</td>
        </tr>
        <tr>
          <td id="L150" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="150"></td>
          <td id="LC150" class="blob-code blob-code-inner js-file-line">      appropriateness of using or redistributing the Work and assume any</td>
        </tr>
        <tr>
          <td id="L151" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="151"></td>
          <td id="LC151" class="blob-code blob-code-inner js-file-line">      risks associated with Your exercise of permissions under this License.</td>
        </tr>
        <tr>
          <td id="L152" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="152"></td>
          <td id="LC152" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L153" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="153"></td>
          <td id="LC153" class="blob-code blob-code-inner js-file-line">   8. Limitation of Liability. In no event and under no legal theory,</td>
        </tr>
        <tr>
          <td id="L154" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="154"></td>
          <td id="LC154" class="blob-code blob-code-inner js-file-line">      whether in tort (including negligence), contract, or otherwise,</td>
        </tr>
        <tr>
          <td id="L155" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="155"></td>
          <td id="LC155" class="blob-code blob-code-inner js-file-line">      unless required by applicable law (such as deliberate and grossly</td>
        </tr>
        <tr>
          <td id="L156" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="156"></td>
          <td id="LC156" class="blob-code blob-code-inner js-file-line">      negligent acts) or agreed to in writing, shall any Contributor be</td>
        </tr>
        <tr>
          <td id="L157" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="157"></td>
          <td id="LC157" class="blob-code blob-code-inner js-file-line">      liable to You for damages, including any direct, indirect, special,</td>
        </tr>
        <tr>
          <td id="L158" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="158"></td>
          <td id="LC158" class="blob-code blob-code-inner js-file-line">      incidental, or consequential damages of any character arising as a</td>
        </tr>
        <tr>
          <td id="L159" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="159"></td>
          <td id="LC159" class="blob-code blob-code-inner js-file-line">      result of this License or out of the use or inability to use the</td>
        </tr>
        <tr>
          <td id="L160" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="160"></td>
          <td id="LC160" class="blob-code blob-code-inner js-file-line">      Work (including but not limited to damages for loss of goodwill,</td>
        </tr>
        <tr>
          <td id="L161" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="161"></td>
          <td id="LC161" class="blob-code blob-code-inner js-file-line">      work stoppage, computer failure or malfunction, or any and all</td>
        </tr>
        <tr>
          <td id="L162" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="162"></td>
          <td id="LC162" class="blob-code blob-code-inner js-file-line">      other commercial damages or losses), even if such Contributor</td>
        </tr>
        <tr>
          <td id="L163" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="163"></td>
          <td id="LC163" class="blob-code blob-code-inner js-file-line">      has been advised of the possibility of such damages.</td>
        </tr>
        <tr>
          <td id="L164" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="164"></td>
          <td id="LC164" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L165" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="165"></td>
          <td id="LC165" class="blob-code blob-code-inner js-file-line">   9. Accepting Warranty or Additional Liability. While redistributing</td>
        </tr>
        <tr>
          <td id="L166" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="166"></td>
          <td id="LC166" class="blob-code blob-code-inner js-file-line">      the Work or Derivative Works thereof, You may choose to offer,</td>
        </tr>
        <tr>
          <td id="L167" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="167"></td>
          <td id="LC167" class="blob-code blob-code-inner js-file-line">      and charge a fee for, acceptance of support, warranty, indemnity,</td>
        </tr>
        <tr>
          <td id="L168" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="168"></td>
          <td id="LC168" class="blob-code blob-code-inner js-file-line">      or other liability obligations and/or rights consistent with this</td>
        </tr>
        <tr>
          <td id="L169" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="169"></td>
          <td id="LC169" class="blob-code blob-code-inner js-file-line">      License. However, in accepting such obligations, You may act only</td>
        </tr>
        <tr>
          <td id="L170" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="170"></td>
          <td id="LC170" class="blob-code blob-code-inner js-file-line">      on Your own behalf and on Your sole responsibility, not on behalf</td>
        </tr>
        <tr>
          <td id="L171" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="171"></td>
          <td id="LC171" class="blob-code blob-code-inner js-file-line">      of any other Contributor, and only if You agree to indemnify,</td>
        </tr>
        <tr>
          <td id="L172" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="172"></td>
          <td id="LC172" class="blob-code blob-code-inner js-file-line">      defend, and hold each Contributor harmless for any liability</td>
        </tr>
        <tr>
          <td id="L173" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="173"></td>
          <td id="LC173" class="blob-code blob-code-inner js-file-line">      incurred by, or claims asserted against, such Contributor by reason</td>
        </tr>
        <tr>
          <td id="L174" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="174"></td>
          <td id="LC174" class="blob-code blob-code-inner js-file-line">      of your accepting any such warranty or additional liability.</td>
        </tr>
        <tr>
          <td id="L175" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="175"></td>
          <td id="LC175" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L176" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="176"></td>
          <td id="LC176" class="blob-code blob-code-inner js-file-line">   END OF TERMS AND CONDITIONS</td>
        </tr>
        <tr>
          <td id="L177" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="177"></td>
          <td id="LC177" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L178" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="178"></td>
          <td id="LC178" class="blob-code blob-code-inner js-file-line">   APPENDIX: How to apply the Apache License to your work.</td>
        </tr>
        <tr>
          <td id="L179" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="179"></td>
          <td id="LC179" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L180" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="180"></td>
          <td id="LC180" class="blob-code blob-code-inner js-file-line">      To apply the Apache License to your work, attach the following</td>
        </tr>
        <tr>
          <td id="L181" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="181"></td>
          <td id="LC181" class="blob-code blob-code-inner js-file-line">      boilerplate notice, with the fields enclosed by brackets "[]"</td>
        </tr>
        <tr>
          <td id="L182" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="182"></td>
          <td id="LC182" class="blob-code blob-code-inner js-file-line">      replaced with your own identifying information. (Don't include</td>
        </tr>
        <tr>
          <td id="L183" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="183"></td>
          <td id="LC183" class="blob-code blob-code-inner js-file-line">      the brackets!)  The text should be enclosed in the appropriate</td>
        </tr>
        <tr>
          <td id="L184" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="184"></td>
          <td id="LC184" class="blob-code blob-code-inner js-file-line">      comment syntax for the file format. We also recommend that a</td>
        </tr>
        <tr>
          <td id="L185" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="185"></td>
          <td id="LC185" class="blob-code blob-code-inner js-file-line">      file or class name and description of purpose be included on the</td>
        </tr>
        <tr>
          <td id="L186" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="186"></td>
          <td id="LC186" class="blob-code blob-code-inner js-file-line">      same "printed page" as the copyright notice for easier</td>
        </tr>
        <tr>
          <td id="L187" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="187"></td>
          <td id="LC187" class="blob-code blob-code-inner js-file-line">      identification within third-party archives.</td>
        </tr>
        <tr>
          <td id="L188" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="188"></td>
          <td id="LC188" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L189" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="189"></td>
          <td id="LC189" class="blob-code blob-code-inner js-file-line">   Copyright [yyyy] [name of copyright owner]</td>
        </tr>
        <tr>
          <td id="L190" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="190"></td>
          <td id="LC190" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L191" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="191"></td>
          <td id="LC191" class="blob-code blob-code-inner js-file-line">   Licensed under the Apache License, Version 2.0 (the "License");</td>
        </tr>
        <tr>
          <td id="L192" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="192"></td>
          <td id="LC192" class="blob-code blob-code-inner js-file-line">   you may not use this file except in compliance with the License.</td>
        </tr>
        <tr>
          <td id="L193" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="193"></td>
          <td id="LC193" class="blob-code blob-code-inner js-file-line">   You may obtain a copy of the License at</td>
        </tr>
        <tr>
          <td id="L194" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="194"></td>
          <td id="LC194" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L195" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="195"></td>
          <td id="LC195" class="blob-code blob-code-inner js-file-line">       http://www.apache.org/licenses/LICENSE-2.0</td>
        </tr>
        <tr>
          <td id="L196" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="196"></td>
          <td id="LC196" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L197" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="197"></td>
          <td id="LC197" class="blob-code blob-code-inner js-file-line">   Unless required by applicable law or agreed to in writing, software</td>
        </tr>
        <tr>
          <td id="L198" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="198"></td>
          <td id="LC198" class="blob-code blob-code-inner js-file-line">   distributed under the License is distributed on an "AS IS" BASIS,</td>
        </tr>
        <tr>
          <td id="L199" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="199"></td>
          <td id="LC199" class="blob-code blob-code-inner js-file-line">   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.</td>
        </tr>
        <tr>
          <td id="L200" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="200"></td>
          <td id="LC200" class="blob-code blob-code-inner js-file-line">   See the License for the specific language governing permissions and</td>
        </tr>
        <tr>
          <td id="L201" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="201"></td>
          <td id="LC201" class="blob-code blob-code-inner js-file-line">   limitations under the License.</td>
        </tr>
        <tr>
          <td id="L202" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="202"></td>
          <td id="LC202" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L203" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="203"></td>
          <td id="LC203" class="blob-code blob-code-inner js-file-line">## Some of TensorFlow's code is derived from Caffe, which is subject to the following copyright notice:</td>
        </tr>
        <tr>
          <td id="L204" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="204"></td>
          <td id="LC204" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L205" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="205"></td>
          <td id="LC205" class="blob-code blob-code-inner js-file-line">COPYRIGHT</td>
        </tr>
        <tr>
          <td id="L206" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="206"></td>
          <td id="LC206" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L207" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="207"></td>
          <td id="LC207" class="blob-code blob-code-inner js-file-line">All contributions by the University of California:</td>
        </tr>
        <tr>
          <td id="L208" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="208"></td>
          <td id="LC208" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L209" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="209"></td>
          <td id="LC209" class="blob-code blob-code-inner js-file-line">Copyright (c) 2014, The Regents of the University of California (Regents)</td>
        </tr>
        <tr>
          <td id="L210" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="210"></td>
          <td id="LC210" class="blob-code blob-code-inner js-file-line">All rights reserved.</td>
        </tr>
        <tr>
          <td id="L211" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="211"></td>
          <td id="LC211" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L212" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="212"></td>
          <td id="LC212" class="blob-code blob-code-inner js-file-line">All other contributions:</td>
        </tr>
        <tr>
          <td id="L213" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="213"></td>
          <td id="LC213" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L214" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="214"></td>
          <td id="LC214" class="blob-code blob-code-inner js-file-line">Copyright (c) 2014, the respective contributors</td>
        </tr>
        <tr>
          <td id="L215" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="215"></td>
          <td id="LC215" class="blob-code blob-code-inner js-file-line">All rights reserved.</td>
        </tr>
        <tr>
          <td id="L216" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="216"></td>
          <td id="LC216" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L217" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="217"></td>
          <td id="LC217" class="blob-code blob-code-inner js-file-line">Caffe uses a shared copyright model: each contributor holds copyright over</td>
        </tr>
        <tr>
          <td id="L218" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="218"></td>
          <td id="LC218" class="blob-code blob-code-inner js-file-line">their contributions to Caffe. The project versioning records all such</td>
        </tr>
        <tr>
          <td id="L219" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="219"></td>
          <td id="LC219" class="blob-code blob-code-inner js-file-line">contribution and copyright details. If a contributor wants to further mark</td>
        </tr>
        <tr>
          <td id="L220" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="220"></td>
          <td id="LC220" class="blob-code blob-code-inner js-file-line">their specific copyright on a particular contribution, they should indicate</td>
        </tr>
        <tr>
          <td id="L221" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="221"></td>
          <td id="LC221" class="blob-code blob-code-inner js-file-line">their copyright solely in the commit message of the change when it is</td>
        </tr>
        <tr>
          <td id="L222" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="222"></td>
          <td id="LC222" class="blob-code blob-code-inner js-file-line">committed.</td>
        </tr>
        <tr>
          <td id="L223" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="223"></td>
          <td id="LC223" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L224" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="224"></td>
          <td id="LC224" class="blob-code blob-code-inner js-file-line">LICENSE</td>
        </tr>
        <tr>
          <td id="L225" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="225"></td>
          <td id="LC225" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L226" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="226"></td>
          <td id="LC226" class="blob-code blob-code-inner js-file-line">Redistribution and use in source and binary forms, with or without</td>
        </tr>
        <tr>
          <td id="L227" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="227"></td>
          <td id="LC227" class="blob-code blob-code-inner js-file-line">modification, are permitted provided that the following conditions are met:</td>
        </tr>
        <tr>
          <td id="L228" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="228"></td>
          <td id="LC228" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L229" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="229"></td>
          <td id="LC229" class="blob-code blob-code-inner js-file-line">1. Redistributions of source code must retain the above copyright notice, this</td>
        </tr>
        <tr>
          <td id="L230" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="230"></td>
          <td id="LC230" class="blob-code blob-code-inner js-file-line">   list of conditions and the following disclaimer.</td>
        </tr>
        <tr>
          <td id="L231" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="231"></td>
          <td id="LC231" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L232" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="232"></td>
          <td id="LC232" class="blob-code blob-code-inner js-file-line">2. Redistributions in binary form must reproduce the above copyright notice,</td>
        </tr>
        <tr>
          <td id="L233" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="233"></td>
          <td id="LC233" class="blob-code blob-code-inner js-file-line">   this list of conditions and the following disclaimer in the documentation</td>
        </tr>
        <tr>
          <td id="L234" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="234"></td>
          <td id="LC234" class="blob-code blob-code-inner js-file-line">   and/or other materials provided with the distribution.</td>
        </tr>
        <tr>
          <td id="L235" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="235"></td>
          <td id="LC235" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L236" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="236"></td>
          <td id="LC236" class="blob-code blob-code-inner js-file-line">   THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND</td>
        </tr>
        <tr>
          <td id="L237" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="237"></td>
          <td id="LC237" class="blob-code blob-code-inner js-file-line">   ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED</td>
        </tr>
        <tr>
          <td id="L238" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="238"></td>
          <td id="LC238" class="blob-code blob-code-inner js-file-line">   WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE</td>
        </tr>
        <tr>
          <td id="L239" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="239"></td>
          <td id="LC239" class="blob-code blob-code-inner js-file-line">   DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR</td>
        </tr>
        <tr>
          <td id="L240" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="240"></td>
          <td id="LC240" class="blob-code blob-code-inner js-file-line">   ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES</td>
        </tr>
        <tr>
          <td id="L241" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="241"></td>
          <td id="LC241" class="blob-code blob-code-inner js-file-line">   (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;</td>
        </tr>
        <tr>
          <td id="L242" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="242"></td>
          <td id="LC242" class="blob-code blob-code-inner js-file-line">   LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND</td>
        </tr>
        <tr>
          <td id="L243" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="243"></td>
          <td id="LC243" class="blob-code blob-code-inner js-file-line">   ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT</td>
        </tr>
        <tr>
          <td id="L244" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="244"></td>
          <td id="LC244" class="blob-code blob-code-inner js-file-line">   (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS</td>
        </tr>
        <tr>
          <td id="L245" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="245"></td>
          <td id="LC245" class="blob-code blob-code-inner js-file-line">   SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.</td>
        </tr>
        <tr>
          <td id="L246" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="246"></td>
          <td id="LC246" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L247" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="247"></td>
          <td id="LC247" class="blob-code blob-code-inner js-file-line">CONTRIBUTION AGREEMENT</td>
        </tr>
        <tr>
          <td id="L248" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="248"></td>
          <td id="LC248" class="blob-code blob-code-inner js-file-line">
</td>
        </tr>
        <tr>
          <td id="L249" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="249"></td>
          <td id="LC249" class="blob-code blob-code-inner js-file-line">By contributing to the BVLC/caffe repository through pull-request, comment,</td>
        </tr>
        <tr>
          <td id="L250" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="250"></td>
          <td id="LC250" class="blob-code blob-code-inner js-file-line">or otherwise, the contributor releases their content to the</td>
        </tr>
        <tr>
          <td id="L251" class="blob-num js-line-number js-code-nav-line-number js-blob-rnum" data-line-number="251"></td>
          <td id="LC251" class="blob-code blob-code-inner js-file-line">license and copyright terms herein.</td>
        </tr>
  </tbody></table>
</div>

  <details class="details-reset details-overlay BlobToolbar position-absolute js-file-line-actions dropdown d-none" aria-hidden="true">
    <summary class="btn-octicon ml-0 px-2 p-0 color-bg-default border color-border-default rounded-2" aria-label="Inline file action toolbar" aria-haspopup="menu" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-kebab-horizontal">
    <path d="M8 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zM1.5 9a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm13 0a1.5 1.5 0 100-3 1.5 1.5 0 000 3z"></path>
</svg>
    </summary>
    <details-menu role="menu" data-focus-trap="active"><span class="sentinel" tabindex="0" aria-hidden="true"></span>

      <ul class="BlobToolbar-dropdown dropdown-menu dropdown-menu-se ml-2 mt-2" style="width:185px">
        <li>
          <clipboard-copy role="menuitem" class="dropdown-item" id="js-copy-lines" style="cursor:pointer;" aria-label="Copy lines" tabindex="0">
            Copy lines
          </clipboard-copy>
        </li>
        <li>
          <clipboard-copy role="menuitem" class="dropdown-item" id="js-copy-permalink" style="cursor:pointer;" aria-label="Copy permalink" tabindex="0">
            Copy permalink
          </clipboard-copy>
        </li>
        <li><a class="dropdown-item js-update-url-with-hash" id="js-view-git-blame" role="menuitem" href="https://github.com/tensorflow/tensorflow/blame/dbaff50b56184643e78582f9322dd5a2060916df/LICENSE">View git blame</a></li>
          <li><a class="dropdown-item" id="js-new-issue" role="menuitem" href="/tensorflow/tensorflow/issues/new">Reference in new issue</a></li>
      </ul>
    <span class="sentinel" tabindex="0" aria-hidden="true"></span></details-menu>
  </details>

    </div>

    </div>


  

  <details class="details-reset details-overlay details-overlay-dark" id="jumpto-line-details-dialog">
    <summary data-hotkey="l" aria-label="Jump to line" role="button"></summary>
    <details-dialog class="Box Box--overlay d-flex flex-column anim-fade-in fast linejump" aria-label="Jump to line" role="dialog" aria-modal="true">
      <!-- '"` --><!-- </textarea></xmp> --><form class="js-jump-to-line-form Box-body d-flex" data-turbo="false" action="" accept-charset="UTF-8" method="get">
        <input class="form-control flex-auto mr-3 linejump-input js-jump-to-line-field" type="text" placeholder="Jump to line…" aria-label="Jump to line" autofocus="">
          <button data-close-dialog="" type="submit" data-view-component="true" class="btn">    Go
</button>
</form>    </details-dialog>
  </details>



</div>

  </div>


  </div>

  </turbo-frame>


    </main>
  </div>

  </div>
