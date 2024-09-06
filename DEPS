# This file is used to manage Vulkan dependencies for several repos. It is
# used by gclient to determine what version of each dependency to check out, and
# where.

# Avoids the need for a custom root variable.
use_relative_paths = True
git_dependencies = 'SYNC'

vars = {
  'chromium_git': 'https://chromium.googlesource.com',

  # Current revision of glslang, the Khronos SPIRV compiler.
  'glslang_revision': '79c4235085c5eb86ed78b034d94e03f7b3b5daef',

  # Current revision of Lunarg VulkanTools
  'lunarg_vulkantools_revision': 'a24a94aa0d1fc4e5556bdf9c6b2afe8eacc55326',

  # Current revision of spirv-cross, the Khronos SPIRV cross compiler.
  'spirv_cross_revision': 'b8fcf307f1f347089e3c46eb4451d27f32ebc8d3',

  # Current revision fo the SPIRV-Headers Vulkan support library.
  'spirv_headers_revision': 'efb6b4099ddb8fa60f62956dee592c4b94ec6a49',

  # Current revision of SPIRV-Tools for Vulkan.
  'spirv_tools_revision': 'f914d9c8a4bdcffb736bac206fbd858fe9bd424d',

  # Current revision of Khronos Vulkan-Headers.
  'vulkan_headers_revision': 'c6391a7b8cd57e79ce6b6c832c8e3043c4d9967b',

  # Current revision of Khronos Vulkan-Loader.
  'vulkan_loader_revision': 'c758bac8bf1580b5018adafd3a2ec709237b0134',

  # Current revision of Khronos Vulkan-Tools.
  'vulkan_tools_revision': '4c63e845962ff3b197855f3ae4907a47d0863f5a',

  # Current revision of Khronos Vulkan-Utility-Libraries.
  'vulkan_utility_libraries_revision': 'fbb4db92c6b2ac09003b2b8e5ceb978f4f2dda71',

  # Current revision of Khronos Vulkan-ValidationLayers.
  'vulkan_validation_revision': 'e695f4345b9065293eab1adcfa48a4f73c647db7',
}

deps = {
  'glslang/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/glslang@{glslang_revision}',
  },

  'lunarg-vulkantools/src': {
    'url': '{chromium_git}/external/github.com/LunarG/VulkanTools@{lunarg_vulkantools_revision}',
  },

  'spirv-cross/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Cross@{spirv_cross_revision}',
  },

  'spirv-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Headers@{spirv_headers_revision}',
  },

  'spirv-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/SPIRV-Tools@{spirv_tools_revision}',
  },

  'vulkan-headers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Headers@{vulkan_headers_revision}',
  },

  'vulkan-loader/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Loader@{vulkan_loader_revision}',
  },

  'vulkan-tools/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Tools@{vulkan_tools_revision}',
  },

  'vulkan-utility-libraries/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-Utility-Libraries@{vulkan_utility_libraries_revision}',
  },

  'vulkan-validation-layers/src': {
    'url': '{chromium_git}/external/github.com/KhronosGroup/Vulkan-ValidationLayers@{vulkan_validation_revision}',
  },
}
