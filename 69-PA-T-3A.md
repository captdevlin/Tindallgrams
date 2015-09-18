---
layout: tindallgram
date: Jan 14 1969
from: PA/Chief, Apollo Data Priority Coordination
serial: 69-PA-T-3A
subject: Operations required for communication loss on F and G are sure better than on C'
---
I think we have pretty well establised how to handle a communication
loss situation on the F and G missions. In effect, we have defined
which Block data must be sent and what onboard cis-lunar navigation
needs to be carried out. In both cases, of course, it is possible
to cut back substantially from the C' techniques. This is because
we feel it is reasonable to assume that the LM provides a "perfect"
backup for the CSM communications.

#BLOCK DATA

We established a ground rule that it is only necessary to send Block
data for short situations when either the LM is not available _or_ if
sufficient time to use the LM is not available. Following is a table
of all the Block data transmissions planned for F and G giving the
time of transmission for the abort opportunity which it would be used for:

_Time of Transmission_|_Time of Abort Maneuver_
----------------------|------------------------
During earth orbit    | TLI + 90 minutes. CSM only, direct return
LOI - 15              | PC + 2 for fast return following flyby
Pre LOI₁              | TEI₁&₂ assuming perfect LOI₁
Pre LOI₂              | TEI₂ Update and TEI₃ assuming no LOI₂
Post LOI              | For TEI after sleep
Pre LM Jettison       | TEI 2 revs from jettison
After LM Jettison     | C' rev by rev technique except during sleep

In addition, remember the crew has the capability of using the GNCS
(P37) to compute their own return-to-earth maneuvers in the event of a
communication loss. In order to simplify the crew's procedures, we
intend to transmit a small amount of additional information for use a
first guess in the operation of P37. Specifically MCC-H will periodically
send the crew values of the landing area (CLA), the maneuver magnitude
(∆V), and the burn ignition time (TIG) for possible future abort times.

#CIS-LUNAR NAVIGATION

As you recall on C', the onboard capacity for cis-lunar navigation
using P23 was thoroughly exercised and proven to be an excellent system.
Furthermore, it appears that Jim Lovell was able to do his job just
about as well in the beginning as he was later in the mission, indicating
that inflight training is not particularly necessary. Based
on this experience, only two batches of P23 star/earth horizon navigation
sightings shall be scheduled on the entire F and G flights. In
order to get the most from these two periods, one should be scheduled
before TLI + 5 hours and the other after TLI + 14 hours, if it is convenient
to do so. The advantage of making the first batch that early
is that it will permit the MCC-H to make an accurate determination of
the actual horizon altitude the CMP is using in order to update the
CMC in real time just as we did on C'. To do this it is necessary
that the observations be made in altitude less than 50,000 n.m. and
preferably lower than 35,000, which is the altitude at TLI + 5 hours.
I would like to point out that the horizon Jim Lovell used so successfully
was a sort of nebulous one of his choice and was not well defined
making it unreliable to use the "C'" horizon altitude for the F and G
missions. Althought not disasterous, a good knowledge of the horizon
substantially improves navigation prior to entry which is when it is
most important in the event of communication loss. Whatever that is.

Recognize that implicit in this plan of scheduling only two batches
of observations early in the translunar coast is that there can be
no independent onboard confirmation of the MSFN navigation which was
considered so important to insure that we miss the moon on C'.

Math Physics Branch of MPAD has been requested to develop a P23 tracking
schedule to be used for transearth navigation in the event of no
communication. this schedule will be included in the Flight Plan
labeled "loss of communication contingency."

As you recall, the primary purpose of onboard navigation during transearth
coast was for conditioning the W-matrix. We have selected a
procedure for F and G which makes it possible to eliminate that operation.
Specifically, we have concluded that a crossover point exists
at 30 hours before entry, which has the following characteristics. If
communication has been lost prior to that time, the onboard system is
capable of providing acceptable navigation, maneuver targeting, nd
entry initialization starting from scratch with no special W-matrix
conditioning. (The flight path angle error at entry should be no
greater than 0.5° under the worse conditions.) In addition, it has been
shown that the MSFN will be sufficiently accurate at EI - 30 hours
that in the event of subsequent communication loss there is no need
to perform onboard navigation but rather the crew may safely return
to earth using the data supplied for that purpose at EI - 30 by the
MCC-H. In other words, the same procedure used on C' at EI - 15 will
be carried out on F and G at EI - 30. Namely, spacecraft state vectors
will be updated and the crew will be provided with midcourse maneuver
targeting and entry pad data needed to complete the mission without
further communication.

In summary, F and G operations associated with communication loss are
being considerably simplified from those used on C'. Utilization of
LM communications makes it possible to markly reduce the number of
abort Block data pad messages; the onboard and MSFN navigation performance
experienced on C' permits us to reduce onboard navigation
to a total of only two batches of star/horizon observations. No
special procedures are required for W-matrix initialization. I'd
call that a giant step in the right direction!
