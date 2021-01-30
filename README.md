# meeting_scheduler_Rest

The meeting schduler can be decomposed in following way.

   * Create meeting   * update meeting * delete meeting
   * Register for meeting * unregister for meeting * create user
   * Get List of all meetings * get data about individual meeting

Meeting Scheduler: Requests and Responses

   * Create Meeting : Requests  -> Title , Description ,Time , User ID
                      Responses ->  Message , Summary , Meeting URL , Participants

   * Update Meeting : Requests  -> Title , Description ,Time , Meeting ID , User ID
                      Responses -> Messages , Summary, Meeting URL , Participants

   * Delete Meeting : Requests  -> Meeting ID , User ID
                      Responses -> Message

   * Register for Meeting : Requests  -> User ID , Meeting ID
                            Responses -> Message, User Info , Meeting Info , Unregistration Link

   * Unregister from Meeting : Requests  -> User ID , Meeting ID
                               Responses -> Message , User Info , Meeting Info , Registration Link

   * Create User : Requests  -> First Name , Last Name , Email , Password
                   Responses -> Message , Summary

