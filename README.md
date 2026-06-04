#import <UIKit/UIKit.h>

@interface ViewController : UIViewController

@property (weak, nonatomic) IBOutlet UISegmentedControl *categoriaSegment;
@property (weak, nonatomic) IBOutlet UILabel *datoLabel;

- (IBAction)mostrarDato:(id)sender;
