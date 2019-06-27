  UART_PutRAMString( UARTString1 )
  {  while( *String != 0x00 )  
  {   while( BusyUART2( ) );   WriteUART2( *String++ ); 
  }
  } 
  
