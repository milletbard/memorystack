<template>
  <div id="features-section" class="container mt-11 is-hidden-mobile">
    <div class="columns is-centered">
      <div class="column is-6 text-center">
        <h2>Features</h2>
        <p class="mt-2" style="font-size: 1rem;">
          We make it simple by un-complicating the platform with our enhanced
          features. Easy escalation policies, suppressing repeat incidents,
          activity logs and more.
        </p>
      </div>
    </div>
    <div class="columns is-centered mt-2">
      <div class="column is-10">
        <div class="columns">
          <div class="column is-2">
            <ul>
              <li class="mt-1">
                <button
                  id="features-incidents"
                  data-target="incidents"
                  class="button is-text features-nav active"
                  type="button"
                >Incidents</button>
              </li>
              <li class="mt-1">
                <button
                  id="features-services"
                  data-target="services"
                  class="button is-text features-nav"
                  type="button"
                >Services</button>
              </li>
              <li class="mt-1">
                <button
                  id="features-escalations"
                  data-target="escalations"
                  class="button is-text features-nav"
                  type="button"
                >Escalations</button>
              </li>
              <li class="mt-1">
                <button
                  id="features-reports"
                  data-target="reports"
                  class="button is-text features-nav"
                  type="button"
                >Reports</button>
              </li>
              <li class="mt-1">
                <button
                  id="features-alerts"
                  data-target="alerts"
                  class="button is-text features-nav"
                  type="button"
                >Alerts</button>
              </li>
              <li class="mt-1">
                <button
                  id="others-alerts"
                  data-target="other-features"
                  class="button is-text features-nav"
                  type="button"
                >Other features</button>
              </li>
            </ul>
          </div>
          <div id="incidents-cards" class="column is-9 feature-cards">
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Group repeat incidents</h3>
                  <p class="mt-1">
                    Incidents which are repeated are automatically grouped
                    together telling you how many times it has occurred along
                    with it's first occurrence and last occurrence.
                  </p>
                </div>
              </div>
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Mute incidents</h3>
                  <p class="mt-1">
                    Mute an incident for a period of time, we will not send any
                    alerts but still create an incident and group them too.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Supress repeat incidents</h3>
                  <p class="mt-1">
                    No repeat alarms, no noise as long as you are working on
                    resolving the incidents.
                  </p>
                </div>
              </div>
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Reassign incidents</h3>
                  <p class="mt-1">
                    Not the right person to handle the incident? Reassign easily
                    to the one who would.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Public incidents</h3>
                  <p class="mt-1">
                    Anyone with the link to your incident can access it in
                    read-only mode and stay updated.
                  </p>
                </div>
              </div>
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Detailed activity log</h3>
                  <p class="mt-1">
                    Bring in more transparency with detailed activity log of
                    alerts, reassigns, incident status changes and repeat events
                    for same incident.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Auto resolve incidents</h3>
                  <p class="mt-1">
                    Our integrations make sure that incidents are resolved
                    automatically on Spike when they are fixed on your
                    monitoring tool.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div id="services-cards" class="column is-10 is-hidden feature-cards">
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Unlimited services</h3>
                  <p class="mt-1">
                    Come full circle by adding incident tracking to all your
                    services. Scope your incidents, reports and health of each
                    service.
                  </p>
                </div>
              </div>
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Affected services</h3>
                  <p class="mt-1">
                    Monitor the services which are affected the most by open
                    incidents. Prioritise and resolve to increase customer
                    satisfaction.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Multiple integrations</h3>
                  <p class="mt-1">
                    Your service relies on multiple tools. Integrate with all
                    your tools for every service to track platform health
                    better.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column">
                <a href="/services" class="bold">
                  Learn more
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    style="fill: var(--blue); vertical-align: middle;"
                  >
                    <path fill="none" d="M0 0h24v24H0V0z" />
                    <path d="M16.01 11H4v2h12.01v3L20 12l-3.99-4v3z" />
                  </svg>
                </a>
              </div>
            </div>
          </div>
          <div id="escalations-cards" class="column is-10 is-hidden feature-cards">
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Simple escalation policies</h3>
                  <p class="mt-1">
                    Alert one or more persons at the same time. Alert via phone
                    prefered channel to every team member with time intervals.
                  </p>
                </div>
              </div>
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Repeat escalations</h3>
                  <p class="mt-1">
                    We repeat escalations so your team doesn't miss an incident
                    in it's
                    <b>triggered</b> state.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Acknowledge timeouts</h3>
                  <p class="mt-1">
                    Set a timeout for an incident which is acknowledged but not
                    resolved yet. This will start the escalations again so
                    no-one misses the incident affecting your customers.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column">
                <a href="/reports" class="bold">
                  Learn more
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    style="fill: var(--blue); vertical-align: middle;"
                  >
                    <path fill="none" d="M0 0h24v24H0V0z" />
                    <path d="M16.01 11H4v2h12.01v3L20 12l-3.99-4v3z" />
                  </svg>
                </a>
              </div>
            </div>
          </div>
          <div id="reports-cards" class="column is-10 is-hidden feature-cards">
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">MTTR and MTTA</h3>
                  <p class="mt-1">
                    Mean Time To Resolve and Mean Time to Acknowledge for your
                    entire platform broken down at service level.
                  </p>
                </div>
              </div>
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Real time platform health</h3>
                  <p class="mt-1">
                    Get a real time snapshot of your platform's health. Monitory
                    by open incidents and resolve for every service.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Reports in your inbox</h3>
                  <p class="mt-1">
                    We send you timely reports directly in your inbox. Ones that
                    you can share with your team and start a dialogue.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column">
                <a href="/reports" class="bold">
                  Learn more
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    style="fill: var(--blue); vertical-align: middle;"
                  >
                    <path fill="none" d="M0 0h24v24H0V0z" />
                    <path d="M16.01 11H4v2h12.01v3L20 12l-3.99-4v3z" />
                  </svg>
                </a>
              </div>
            </div>
          </div>
          <div id="alerts-cards" class="column is-10 is-hidden feature-cards">
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Unlimited alerts</h3>
                  <p class="mt-1">
                    We provide you unlimited alerts across all the supported
                    channels. No more predicting your monthly billing cycle.
                  </p>
                </div>
              </div>
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Actionable alerts</h3>
                  <p class="mt-1">
                    We have made it easy for you to acknowledge, resolve or
                    escalate incident via phone, email and Slack
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Multiple channels</h3>
                  <p class="mt-1">Spike supports unlimited alerts via email, phone and Slack.</p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column">
                <a href="/alerts" class="bold">
                  Learn more
                  <svg
                    xmlns="http://www.w3.org/2000/svg"
                    width="24"
                    height="24"
                    viewBox="0 0 24 24"
                    style="fill: var(--blue); vertical-align: middle;"
                  >
                    <path fill="none" d="M0 0h24v24H0V0z" />
                    <path d="M16.01 11H4v2h12.01v3L20 12l-3.99-4v3z" />
                  </svg>
                </a>
              </div>
            </div>
          </div>
          <div id="other-features-cards" class="column is-10 is-hidden feature-cards">
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Unlimited team members</h3>
                  <p class="mt-2">
                    Grow your team on Spike with ease. We scale our platform as
                    you grow your team. We also make it easy to remove a member
                    from your team.
                  </p>
                </div>
              </div>
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Multiple roles</h3>
                  <p class="mt-2">
                    We support multiple roles on Spike. Assign and change roles
                    under settings.
                  </p>
                </div>
              </div>
            </div>
            <div class="columns">
              <div class="column is-6 p-1">
                <div
                  class="inner-desc-column p-2"
                  style="border: 1px solid #dee2e6; border-radius: 6px;"
                >
                  <h3 class="bold">Video tutorials</h3>
                  <p class="mt-2">
                    <i>coming soon</i> A few set of short videos to help you get
                    the most out of Spike.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template
>>
