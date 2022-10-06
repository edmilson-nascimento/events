# events
Events / horas SE54


Event 05 / 21 
```abap
FORM set_create_timestamp .

  zmmt1003-uname = sy-uname.
  zmmt1003-datum = sy-datum.
  zmmt1003-uzeit = sy-uzeit.

ENDFORM.                    " SET_CREATE_TIMESTAMP

FORM set_change_timestamp .

  IF status-action EQ 'U'.
    zmmt1003-uname = sy-uname.
    zmmt1003-datum = sy-datum.
    zmmt1003-uzeit = sy-uzeit..
  ENDIF.

ENDFORM.                    " SET_CHANGE_TIMESTAMP


```
