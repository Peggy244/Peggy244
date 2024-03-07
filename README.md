#include <avr/io.h>
#include ,util/delay.h>
int main()
{
DDRD = 0x00;
DDRB =0xFF;
PORTB =0xff;
while(1)
{
PORTB |= (1<<2);
_delay_ms(1000);

}
}
