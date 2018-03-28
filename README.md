# dual-range-angular-slider

Angular 5

dual range input slider syntax:

<dual-range [connect]="true" [min]="min" [max]="max" [step]="step" [(ngModel)]="dualRange" [tooltips]="[ true, true ]"
                                    (ngModelChange)="onChange($event)"></dual-range>