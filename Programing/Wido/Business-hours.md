
# Dias da Semana 

``` HTML
<ion-toolbar class="button-container">
        <div class="button-container">
          <button *ngFor="let day of weekdays; let i = index"
                  [ngClass]="{'active': daysActivated[i]}"
                  (click)="toggleDay(i)">
            <span>{{ day }}</span>
          </button>
        </div>
</ion-toolbar>
```

Ele defina o *index* para que saiba qual ativar e qual desligar

---
## problema 

é que todos desativam quando clicados

```TS
weekdays = ['D', 'S', 'T', 'Q', 'Q', 'S', 'S'];
daysActivated = [false, false, false, false, false, false, false];
```

Provavelmente porque só tem uma propriedade que controla quando os botões estão ativados ou desativados e está ligada a todos: 

- `daysActivated`

o index do `NgFor` serve para todos também.

Obs: Mais pra frente eu vou precisar mudar o `weedays`, para as traduções

 ---
 
## Solução

##### opções:

- Criar um `ngFor` para os turnos (o que já vai ser implementado mais pra frente)


---

<button>
	<span style="color: blue"> This works? </span>
</button>

The fuck, dá pra adicionar HTML aqui

---
# Adicionar Horário 
---
Preciso que se crie um desses quando clicar no botão **+ Adicionar Horário**:

```HTML

  <ion-row class="shift">
        <ion-col class="ion-no-padding">
          <wido-form-datetime
            is-new-style="true"
            label="Das"
            icon-name="time-outline"
            presentation="time"
            display-format="{{ 'BUSINESS_PROFILE_APPOINTMENT_MODAL.TIME_FORMAT' | translate }}"
            [min-date]="minDate"
            [max-date]="maxDate"
            form-control-name="startTime"
            [form-group]="appointmentForm"
            [error-messages]="errorMessages.startTime"
            [error-control]="startTime"
          >
          </wido-form-datetime>
        </ion-col>
        
        <ion-col class="ion-no-padding">
          <wido-form-datetime
            is-new-style="true"
            label="Às"
            icon-name="time-outline"
            presentation="time"
            display-format="{{ 'BUSINESS_PROFILE_APPOINTMENT_MODAL.TIME_FORMAT' | translate }}"
            [min-date]="minDate"
            [max-date]="maxDate"
            form-control-name="endTime"
            [form-group]="appointmentForm"
            [error-messages]="errorMessages.endTime"
            [error-control]="endTime"
          >
          </wido-form-datetime>
        </ion-col>
      </ion-row>
```

É aquela parte das horas

---
### Solução

Talvez criar um component com valores *default*?