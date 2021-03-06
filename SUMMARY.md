# Summary

* [Introduction](README.md)
    * [What's New With 2.1.0](introduction/whats_new_with_210.md)
    * [What's New With 2.0.0](introduction/whats_new_with_200.md)
    * [About This Book](introduction/about_this_book.md)
    * [Author](introduction/author.md)
* [Overview](overview/README.md)
    * [WireBox RefCard](overview/wirebox_refcard.md)
    * [Useful Resources](overview/useful_resources.md)
    * [Features at a Glance](overview/features_at_a_glance.md)
    * [System Requirements](installing_wirebox/system_requirements.md)
* [Installing WireBox](installing_wirebox/README.md)
* [Dependency Injection Explained](dependency_injection_explained/README.md)
* [Getting Jiggy Wit It!](getting_jiggy_wit_it/README.md)
    * [Instance Creations](getting_jiggy_wit_it/instance_creations.md)
    * [Binder Introduction](getting_jiggy_wit_it/binder_introduction.md)
    * [Scoping](getting_jiggy_wit_it/scoping.md)
    * [Eager Init](getting_jiggy_wit_it/eager_init.md)
    * [How WireBox Resolves Dependencies](getting_jiggy_wit_it/how_wirebox_resolves_dependencies.md)
* [WireBox Injector](wirebox_injector/README.md)
    * [Injector Constructor Arguments](wirebox_injector/injector_constructor_arguments.md)
    * [Injection Idioms](wirebox_injector/injection_idioms.md)
    * [Common Methods](wirebox_injector/common_methods.md)
* [Configuring WireBox](configuring_wirebox/README.md)
    * [Binder Configuration Properties](configuring_wirebox/binder_configuration_properties.md)
    * [ColdBox Enhanced Binder](configuring_wirebox/coldbox_enhanced_binder.md)
    * [Types & Scopes](configuring_wirebox/types_of_scopes.md)
    * [Implicit Configuration Settings](configuring_wirebox/implicit_configuration_settings.md)
* [Mapping DSL](mapping_dsl/README.md)
    * [WireBox Configuration](mapping_dsl/wirebox_configuration.md)
    * [Mapping Initiators](mapping_dsl/mapping_initiators.md)
        * [MapDirectory\(\) Influence & Filters](mapping_dsl/mapdirectory_influence_&_filters.md)
    * [Mapping Destinations](mapping_dsl/mapping_destinations.md)
    * [Persistence DSL](mapping_dsl/persistence_dsl.md)
    * [Dependencies DSL](mapping_dsl/dependencies_dsl.md)
        * [Mapping Extra Attributes](mapping_dsl/mapping_extra_attributes.md)
    * [Mapping DSL Examples](mapping_dsl_examples/README.md)
    * [Influence Instances at Runtime](mapping_dsl/influence_instances_at_runtime.md)
* [Component Annotations](componets_annotations/README.md)
    * [Persistence Annotations](componets_annotations/scope_persistence_annotations.md)
    * [CacheBox Annotations](componets_annotations/cachebox_integration.md)
* [Parent Object Definitions](parent_object_definitions/README.md)
* [Virtual Inheritance](virtual_inheritance/README.md)
* [Runtime Mixins\(\)](runtime_mixins/README.md)
* [Injection DSL](injection_dsl/README.md)
    * [ID-Model-Empty Namespace](injection_dsl/id-model-empty_namespace.md)
    * [Provider Namespace](injection_dsl/provider_namespace.md)
    * [WireBox Namespace](injection_dsl/wirebox_namespace.md)
    * [CacheBox Namespace](injection_dsl/cachebox_namespace.md)
    * [EntityService Namespace](injection_dsl/entityservice_namespace.md)
    * [LogBox Namespace](injection_dsl/logbox_namespace.md)
    * [Java Namespace](injection_dsl/java_namespace.md)
    * [ColdBox Namespace](injection_dsl/coldbox_namespace.md)
* [Object Persistence & Thread Safety](object_persistence_&_thread_safety/README.md)
* [ORM Entity Injection](orm_entity_injection/README.md)
* [WireBox Event Model](wirebox_event_model/README.md)
    * [WireBox Events](wirebox_event_model/wirebox_events.md)
    * [WireBox Listeners](wirebox_listeners/README.md)
        * [ColdBox Mode Listener](wirebox_listeners/coldbox_mode_listener.md)
        * [Standalone Mode Listener](wirebox_listeners/standalone_mode_listener.md)
* [Providers](providers/README.md)
    * [Custom Providers](providers/custom_providers.md)
    * [toProvider\(\) closures](providers/toprovider_closures.md)
    * [Virtual Provider Injection DSL](providers/virtual_provider_injection_dsl.md)
    * [Virtual Provider Mapping](providers/virtual_provider_mapping.md)
    * [Virtual Provider Lookup Methods](providers/virtual_provider_lookup_methods.md)
    * [Provider onMissingMethod Proxy](providers/provider_onmissingmethod_proxy.md)
    * [Scope Widening Injection](providers/scope_widening_injection.md)
* [Custom DSL](custom_dsl_builder/README.md)
    * [The DSL Builder Interface](custom_dsl_builder/the_dsl_builder_interface.md)
    * [Registering a Custom DSL](custom_dsl_builder/registering_a_custom_dsl.md)
* [Custom Scopes](custom_scopes/README.md)
    * [The Scope Interface](custom_scopes/the_scope_interface.md)
    * [Scoping Process](custom_scopes/scoping_process.md)
    * [Registering a Custom Scope](custom_scopes/registering_a_custom_scope.md)
* [WireBox Injector Interface](wirebox_injector_interface/README.md)
* [WireBox Object Populator](wirebox_object_populator/README.md)
    * [populateFromXML](wirebox_object_populator/populatefromxml.md)
    * [populateFromQuery](wirebox_object_populator/populatefromquery.md)
    * [populateFromStruct](wirebox_object_populator/populatefromstruct.md)
    * [populateFromQueryWithPreix](wirebox_object_populator/populatefromquerywithpreix.md)
    * [populateFromJSON](wirebox_object_populator/populatefromjson.md)
* [Aspect Oriented Programming](aop/index.md)
    * [Overview](aop/overview.md)
        * [AOP Vocabulary](aop/aop_vocabulary.md)
    * [Activate The AOP Listener](aop/activate_the_aop_listener.md)
    * [Create Your Aspect](aop/create_your_aspect.md)
        * [MethodInvocation Useful Methods](aop/methodinvocation_useful_methods.md)
        * [MethodLogger Aspect](aop/methodlogger_aspect.md)
    * [Aspect Registration](aop/aspect_registration.md)
    * [Aspect Binding](aop/aspect_binding.md)
    * [Auto Aspect Binding](aop/auto_aspect_binding.md)
        * [ClassMatcher Annotation DSL](aop/classmatcher_annotation_dsl.md)
        * [MethodMatcher Annotation DSL](aop/methodmatcher_annotation_dsl.md)
    * [Included Aspects](aop/included_aspects.md)
        * [CFTransaction](aop/cftransaction.md)
        * [HibernateTransaction](aop/hibernate_transaction.md)
        * [MethodLogger](aop/methodlogger.md)
    * [Summary](aop/summaryu.md)

