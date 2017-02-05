## Créer ces propres pipes

    @Pipe({
      name: 'fromNow'
    })
    export class FromNowPipe implements PipeTransform {
      transform(value: Date): string {
        return moment(value).fromNow();
      }
    }
    
usage

    {{myDate | fromNow}}
